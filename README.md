<h3>Trabalho Final – Programando IA com Python</h1>
<ol>
  <li> Leia o arquivo lemonades.csv usando pandas </li>
  <li> Retorne as informações sobre as colunas e as principais estatísticas sobre o dataset </li>
  <li> Realize a limpeza do dataset: 
    <ol>
      <li> Verifique se existe valores nulos </li>
      <li> Verifique e remova, se existir, linhas duplicadas </li>
      <li> Trate os elementos faltantes (interpolação (data) e media) </li>
    </ol>
  </li>
  <li> Adicione uma coluna chamada "Sales" que contém o total de vendas de limão e laranja </li>
  <li> Adicione uma coluna chamada "Revenue" que calcula o lucro (venda*preço) </li>
  <li> Escreva uma função que retorne o lucro total </li>
  <li> Escreva uma função que receba dois parâmetros, dataset e temp(int). Se temp for 1, ele retorna a máxima temperatura observada no conjunto de dados; se 0, retorna a média do período observado; se -1, retorna a temperatura mínima </li>
  <li> Escreva uma função que receba dois parâmetros (dataset, localização) e retorne o dataset com o preço do limão e laranja ajustados em 15% se a localização for 'Park' ou ajustados em 10% se a localização for 'Beach'</li>
  <li> Escreva uma função que receba o dataset como parâmetro e retorne o dataset com uma coluna a mais que mostre o rank de temperatura. O dataset retornado precisa estar ordenado de acordo com rank (descendente) </li>
  <li> Imprima um gráfico de linha que retorne o lucro ao longo do tempo </li>
  <li> Crie um scatter-plot leaflets x sales. Existe alguma correlação entre os dados? (Use a correlação de Pearson e explique o significado do valor obtido por ela) </li>
  <li> Crie um histograma com 10 bins que mostre o lucro (revenue) </li>
  <li> Crie um gráfico de linha que mostre o lucro por tipo de fruta ao longo do tempo </li>
  <li> Ajuste uma Regressão Linear aos dados para predizer vendas usando cada uma das features abaixo: 
    <ol>
      <li> Temperature </li>
      <li> Leaflets </li>
      <li> Price </li>
      <li> Retorne um gráfico com a reta ajustada aos dados para cada feature e diga se ela é uma variável boa ou não para predizer vendas. Comente o resultado obtido </li>
    </ol>
  </li>
  <li> Ajuste uma Regressão Linear aos dados para predizer vendas usando as três features juntas. Comente o resultado obtido </li>
  <li> Generalize o algoritmo de Regressão Linear implementada em sala para que ele possa ser usado para regressão multivariada </li>
  <li> Aplique o algoritmo implementado na questão 16 no conjunto de dados consumo_cerveja.csv usando as mesmas features para treinamento:
    <ol>
      <li> Compare os resultados que você obteve com os resultados obtidos através da Scikit Learning </li>
      <li> Prediga o consumo usando seu modelo e o modelo da sklearn </li>
      <li> Calcule o MSE de ambos </li>
    </ol>
  </li>
</ol>
