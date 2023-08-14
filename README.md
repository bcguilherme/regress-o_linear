# regress-o_linear

Análise de Regressão Linear - Tempo x Venda
Este repositório contém um exemplo de análise de regressão linear aplicada ao relacionamento entre a variável "tempo" e a variável "vendas". A análise foi realizada usando as bibliotecas pandas, numpy, seaborn e statsmodels em Python.

Requisitos
Certifique-se de ter as seguintes bibliotecas instaladas:

pandas
numpy
seaborn
statsmodels
Você pode instalá-las usando o seguinte comando:

Copy code
pip install pandas numpy seaborn statsmodels
Conjunto de Dados
O conjunto de dados utilizado neste exemplo é representado pelas variáveis "tempo" (tempo de experiência) e "vendas". Os dados estão organizados da seguinte maneira:

lua
Copy code
| tempo | vendas |
|-------|--------|
|   1   |   91   |
|   3   |  110   |
|   4   |  106   |
|   4   |  116   |
|   6   |  119   |
|   8   |  129   |
|  10   |  139   |
|  10   |  143   |
|  11   |  138   |
|  13   |  159   |
Análise
Visualização dos Dados

Inicialmente, os dados são carregados e exibidos em um gráfico de dispersão com uma linha de regressão usando a biblioteca Seaborn.

Matriz de Correlação

Uma matriz de correlação é calculada para verificar a relação entre as variáveis "tempo" e "vendas".

Regressão Linear com statsmodels

A biblioteca statsmodels é usada para realizar uma regressão linear simples entre "tempo" (variável independente) e "vendas" (variável dependente). O coeficiente de determinação (R²) e outros parâmetros da regressão são exibidos.

Resíduos

Os resíduos da regressão são calculados e adicionados ao conjunto de dados. Os valores previstos são subtraídos das vendas reais para determinar os resíduos.

Resultados
Os resultados da regressão linear, incluindo o resumo da análise e os resíduos, são impressos na saída. O coeficiente de determinação (R²) é um indicador da qualidade do ajuste do modelo aos dados.

Executando o Código
Para executar o código e visualizar os resultados, você pode criar um ambiente Python com as bibliotecas necessárias instaladas. Em seguida, basta executar o script Python fornecido.

python
Copy code
python nome_do_arquivo.py
Lembre-se de substituir nome_do_arquivo.py pelo nome real do arquivo que contém o código.

Conclusão
Este repositório fornece um exemplo simples de como realizar uma análise de regressão linear usando Python. Sinta-se à vontade para explorar o código e ajustar os parâmetros conforme necessário para seus próprios conjuntos de dados e análises.
