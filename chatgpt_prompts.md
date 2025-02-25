# Resumo de vendas:

Vou consolidar os dados das três plataformas e fornecer um resumo geral das vendas. Isso incluirá o total de vendas, número de pedidos e média de preços, se essas informações estiverem disponíveis nos arquivos.  

Vou processar os arquivos agora.

Os três arquivos possuem a mesma estrutura de colunas, o que facilita a consolidação dos dados. As principais colunas relevantes para o resumo de vendas incluem:  

- **SKU**: Código do produto  
- **product_sold**: Nome do produto  
- **date**: Data da venda  
- **quantity**: Quantidade vendida  
- **unit_price**: Preço unitário  
- **total_price**: Valor total da venda  
- **currency**: Moeda utilizada  
- **discount_value**: Valor do desconto aplicado  

Agora, vou consolidar os dados e calcular:  
1. O total de vendas (somatório de `total_price`).  
2. O número total de pedidos (quantidade de registros).  
3. O preço médio unitário.  

Vou processar essas informações agora.

Aqui está o resumo das vendas consolidadas por plataforma:  

| Plataforma  | Total de Vendas | Total de Pedidos | Preço Médio Unitário |
|------------|----------------|-----------------|---------------------|
| **AliExpress** | $5,120 | 58 pedidos | $88.00 |
| **Etsy** | $5,190 | 56 pedidos | $92.00 |
| **Shopee** | $5,620 | 64 pedidos | $89.00 |
| **TOTAL** | $15,930 | 178 pedidos | $89.67 |

Os valores estão somados em suas respectivas moedas, então se houver diferentes tipos de moedas nos dados, pode ser necessário ajustar para uma conversão correta.  


# ordene as vendas de produtos do mais vendido pra o menos vendido em cada país, mostrando país , produto e quantidade vendida

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

