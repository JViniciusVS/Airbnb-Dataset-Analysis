# Análise do Mercado Airbnb em Seattle

## Visão Geral
Este projeto analisa o mercado do Airbnb em Seattle utilizando um conjunto de dados que fornece várias informações sobre as listagens de propriedades, preços e receitas. O objetivo é ajudar um cliente que está considerando investir em propriedades do Airbnb, fornecendo informações essenciais como preços das propriedades, localização, número de quartos e receita potencial.

## Estudo de Caso
O cliente deseja entender por onde começar o seu negócio no Airbnb, especificamente quais locais são mais rentáveis e em que tipo de propriedades investir. Os principais fatores a serem considerados são:
- **Número de Quartos**: Como o número de quartos afeta o preço.
- **Localização (CEP)**: Quais áreas são mais lucrativas.
- **Potencial de Receita**: Que tipo de receita pode ser esperada com base na sazonalidade e localização.

## Dados
O conjunto de dados utilizado neste projeto contém listagens de Airbnb em Seattle. Ele inclui detalhes como preço, número de quartos e CEP, juntamente com a receita gerada ao longo de um ano.

## Visualizações
Abaixo estão as principais visualizações criadas no Tableau para fornecer insights:

### 1. Preço por CEP (Gráfico de Barras)
Esta visualização mostra o preço médio das listagens de Airbnb, dividido pelos diferentes códigos postais de Seattle. Isso ajuda a identificar quais áreas são mais caras e, potencialmente, mais lucrativas.

### 2. Preço por CEP (Mapa)
Um mapa geográfico mostrando o preço médio por listagem nos diferentes códigos postais de Seattle. Isso fornece uma representação visual de onde as listagens de alto valor estão concentradas, facilitando a localização das áreas de interesse.

### 3. Receita Anual (Gráfico de Linha)
Esta visualização mostra como a receita flutua ao longo do ano. É crucial para entender as tendências sazonais nas reservas de Airbnb, ajudando o cliente a determinar os melhores momentos para esperar alta receita.

### 4. Preço Médio por Quarto (Gráfico de Barras)
Este gráfico mostra o preço médio de uma listagem com base no número de quartos. Ele ajuda o cliente a decidir qual tamanho de propriedade investir, com base em quanto pode ser cobrado por noite.

### 5. Contagem Distinta de Listagens por Quarto (Tabela)
Esta tabela fornece o número de listagens distintas disponíveis por número de quartos. É útil para entender quantas listagens existem em cada categoria de quartos, oferecendo insights sobre a dinâmica de oferta e demanda.

## Principais Insights
- **Localização é Fundamental**: Os CEPs 98109 e 98119 têm preços médios mais altos, sugerindo que podem ser áreas mais lucrativas para investimento.
- **O Número de Quartos Afeta o Preço**: Como esperado, listagens com mais quartos têm preços mais altos. Listagens com seis quartos têm um preço médio de cerca de $584,8, enquanto listagens de um quarto têm um preço médio de $96,2.
- **Tendências Sazonais**: Há um aumento claro na receita durante certos períodos do ano, com um pico no meio do verão, indicando alta demanda turística nessa estação.

## Ferramentas Utilizadas
- **Tableau**: Para criação das visualizações de dados.
- **Conjunto de Dados do Airbnb**: Dados fornecidos sobre as listagens em Seattle, incluindo preços, localização (CEP) e outros detalhes das propriedades.

## Começando
Para visualizar o painel no Tableau ou replicar a análise:
1. Clone este repositório.
2. Abra o arquivo do Tableau e conecte-o ao conjunto de dados fornecido.

## Conclusão
Este projeto ajuda o cliente a tomar decisões informadas sobre o investimento no mercado Airbnb em Seattle. Usando dados para entender as tendências de preços, a lucratividade das localizações e os padrões sazonais de receita, ele pode escolher as melhores áreas e tipos de propriedades para maximizar a receita no Airbnb.
