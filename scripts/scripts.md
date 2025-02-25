#Script 1

import pandas as pd

# Carregar os arquivos CSV
file_paths = {
    "AliExpress": "/mnt/data/Meganium_Sales_Data_-_AliExpress.csv",
    "Etsy": "/mnt/data/Meganium_Sales_Data_-_Etsy.csv",
    "Shopee": "/mnt/data/Meganium_Sales_Data_-_Shopee.csv"
}

# Dicionário para armazenar os dataframes
dataframes = {}

# Ler os arquivos e armazená-los no dicionário
for platform, path in file_paths.items():
    try:
        df = pd.read_csv(path)
        dataframes[platform] = df
    except Exception as e:
        print(f"Erro ao carregar {platform}: {e}")

# Verificar as colunas de cada dataset para entender a estrutura
columns_info = {platform: df.columns.tolist() for platform, df in dataframes.items()}

columns_info


# Script 2

Aqui está a lista de produtos mais vendidos em cada país, ordenada do mais vendido para o menos vendido:  

| País       | Produto                   | Quantidade Vendida |
|-----------|---------------------------|---------------------|
| **Austrália** | NEW MEGANIUM RG CubeXX  | 13  |
|            | NEW MEGANIUM RG28XX       | 8   |
|            | MEGANIUM RG353M           | 5   |
|            | NEW MEGANIUM RG35XX       | 2   |
| **Canadá**   | NEW MEGANIUM RG 40XXV    | 19  |
|            | NEW MEGANIUM RG35XX       | 14  |
|            | NEW MEGANIUM RG28XX       | 11  |
|            | NEW MEGANIUM RG CubeXX    | 2   |
| **França**   | NEW MEGANIUM RG35XX      | 12  |
|            | NEW MEGANIUM RG CubeXX    | 9   |
|            | MEGANIUM RG353M           | 6   |
|            | NEW MEGANIUM RG28XX       | 5   |
|            | NEW MEGANIUM RG 40XXV     | 4   |
| **Alemanha** | NEW MEGANIUM RG 40XXV    | 7   |
|            | NEW MEGANIUM RG28XX       | 7   |
|            | NEW MEGANIUM RG CubeXX    | 5   |
|            | MEGANIUM RG353M           | 3   |
|            | NEW MEGANIUM RG35XX       | 1   |
| **Japão**   | NEW MEGANIUM RG 40XXV    | 11  |
|            | MEGANIUM RG353M           | 6   |
|            | NEW MEGANIUM RG CubeXX    | 5   |
|            | NEW MEGANIUM RG28XX       | 5   |
| **Reino Unido** | NEW MEGANIUM RG35XX  | 7   |
|            | MEGANIUM RG353M           | 5   |
|            | NEW MEGANIUM RG CubeXX    | 1   |
| **EUA**     | MEGANIUM RG353M          | 4   |
|            | NEW MEGANIUM RG CubeXX    | 1   |

