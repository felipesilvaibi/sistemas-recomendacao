# Sistemas de Recomendação
Apresentação de três diferentes abordagens utilizadas por sistemas de recomendação (utilizando ou não Machine Learning). Sendo eles:
  1. Recomendação baseada em Popuridade
  2. Recomendação baseada em Filtragem Colaborativa (similaridade por distância euclidiana - KNN)
  3. Recomendação baseada em Filtragem Colaborativa (similaridade por cosseno - SVD)

## Recomendador baseado em Popularidade
- Recomendador geral baseado apenas na popularidade dos produtos
- Cria o ranking com base na ponderação do score e do somatório de "estrelas" do produto

## Recomendador baseado em Filtragem Colaborativa (recomendação item-item)
- O recomendador por filtragem colaborativa leva em consideração que pessoas pensam da mesma forma ou produtos semelhantes tendem a dar ou receber notas semelhantes

### Algoritmo KNN (similaridade por distância euclidiana)
- Cria a recomendação de produtos relacionados ao produto informado com base na similaridade do produto com outros produtos (sendo a similaridade determinada através da distância euclidiana entre os produtos)

### Algoritmo SVD (similaridade por cosseno)
- Cria a recomendação de produtos relacionados ao produto informado com base na similaridade do produto com outros produtos (sendo a similaridade determinada através do valor do cosseno do ângulo compreendido entre os produtos)

# Organização das Pastas
- data: Todo e qualquer documento utilizado nas análises (.CSV, .XLSX, JSON, ...)
- notebooks: Toda a qualquer análise (sendo arquivo .ipynb ou .py)

# Instalação de Bibliotecas
- Instalar todas as bibliotecas da pasta requirements ($ sudo pip install -r requirements.txt)
