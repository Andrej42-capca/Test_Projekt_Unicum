import pandas as pd
# Чтение Excel-файла
df_excel = pd.read_excel('test.excel.xlsx')

# Посмотреть первые 5 строк
print(df_excel.head())

# Посмотреть информацию о таблице
print(df_excel.info())

data = {
    'Name': ['Alice', 'Bob', 'Charlie'],
    'Age': [25, 30, 35],
    'City': ['New York', 'Los Angeles', 'Chicago']
}
df = pd.DataFrame(data)
print(df)
# Сохранение в CSV
df.to_csv('output.csv', index=False)

# Сохранение в Excel
df.to_excel('output.xlsx', index=False)


