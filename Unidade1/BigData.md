import pandas as pd
df = pd.read_csv("chamados_suporte_ti.csv")
df.head()
df.tail(3)
print(df.shape)
print(df.columns.tolist())
