# Análise de Preços de Alojamentos

Este projeto analisa dados de preços de diferentes tipos de alojamentos, focando na identificação e tratamento de outliers nos valores de preço.

## Dependências

- Python 3.x
- pandas
- seaborn
- matplotlib

## Estrutura do Notebook

1. Importação das Bibliotecas
   - pandas para manipulação de dados
   - seaborn para visualizações estatísticas
   - matplotlib para gráficos

2. Importação do Dataset
   - Carregamento do arquivo 'listings.csv'
   - Seleção das colunas 'room_type' e 'price'

3. Análise Exploratória
   - Visualização dos dados com boxplot
   - Identificação de outliers

4. Tratamento de Outliers
   - Implementação de função para remover outliers
   - Cálculo de médias
   - Substituição de valores

5. Visualização Final
   - Boxplot atualizado após tratamento
