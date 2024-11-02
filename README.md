# Análise de Clusterização e Cálculo de MAE

Este projeto contém um notebook Python que realiza uma análise exploratória e clusterização de dados de pacientes, utilizando o algoritmo KMeans. Além disso, o notebook demonstra o uso da MAE (Mean Absolute Error) para avaliação de erros. As perguntas feitas durante o processo foram adicionadas no notebook para torná-lo mais didático e fácil de seguir.

## Objetivos
- Realizar clusterização de pacientes com base em suas características clínicas.
- Tratar os dados, incluindo preenchimento de valores ausentes e integração de diferentes bases de dados.
- Calcular a média salarial e idade dos pacientes por diferentes regiões e estados.
- Visualizar a relação entre as variáveis por meio de gráficos.
- Calcular o erro absoluto médio (MAE) para avaliar previsões.

## Algoritmos Utilizados
1. **KMeans Clustering**: Utilizado para agrupar os pacientes em diferentes clusters com base nas variáveis 'peso' e 'colesterol'. Foram formados 3 clusters principais, que foram analisados para entender diferenças nos perfis dos pacientes.

2. **MAE (Mean Absolute Error)**: Utilizado para medir o erro entre valores reais e valores previstos, mostrando a média dos erros absolutos.

## Estrutura do Notebook
1. **Carregamento dos Dados**: Foram utilizados três conjuntos de dados:
   - `dados_clinicos.csv`: Informações como peso, colesterol, idade, entre outros.
   - `dados_pacientes.csv`: Informações como classe de trabalho, escolaridade, estado civil, etc.
   - `estado_regiao.csv`: Informações sobre a localização dos pacientes.

2. **Tratamento de Dados**: Tratamento de valores ausentes, preenchendo dados numéricos com a média arredondada e dados categóricos com a moda.

3. **Integração dos Dados**: Combinação das três bases de dados para realizar análises integradas.

4. **Clusterização com KMeans**: Análise de agrupamento utilizando as variáveis 'peso' e 'colesterol'. Foram gerados gráficos para visualizar os clusters formados e os centróides.

5. **Análise Exploratória**:
   - Gráfico de dispersão da relação entre salário e idade, agrupado por gênero.
   - Cálculo da média salarial para os pacientes da região Nordeste.
   - Identificação do estado com a maior média de idade e com o maior número de pacientes com grau de escolaridade 'Mestrado'.

6. **Cálculo de MAE**: Exemplo fictício para demonstrar como calcular o Mean Absolute Error.

## Como Utilizar
1. Clone este repositório:
   ```
   git clone <URL_do_repositorio>
   ```
2. Abra o notebook no Jupyter ou em qualquer ambiente que suporte `.ipynb`.
3. Execute cada célula para ver os gráficos, clusters e cálculos de MAE.

## Requisitos
- Python 3.x
- Bibliotecas: `numpy`, `pandas`, `matplotlib`, `sklearn`

## Resultados
Os principais resultados incluem:
- A formação de 3 clusters distintos com base nas características clínicas dos pacientes.
- Visualizações que mostram a relação entre variáveis como idade, salário, peso e colesterol.
- Identificação de padrões nos dados, como estados com maior escolaridade e análise de risco dos clusters.

## Contribuição
Sinta-se à vontade para contribuir com melhorias no código ou na análise.

## Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

