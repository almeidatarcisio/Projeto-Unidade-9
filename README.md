# Análise de Engajamento de Influenciadores do Instagram com Regressão Linear

## Descrição
Este projeto aborda a análise de dados de influenciadores do Instagram e a predição da taxa de engajamento de 60 dias utilizando um modelo de Regressão Linear. A análise inclui desde o pré-processamento dos dados até a avaliação do modelo por meio de métricas como Mean Squared Error (MSE) e R² Score.

## Estrutura do Projeto
- *Código em Python*: Utiliza bibliotecas como pandas, scikit-learn, matplotlib, e numpy.
- *Pré-processamento*: Conversão de valores com sufixos ('k', 'm', 'b') e percentuais em valores numéricos.
- *Modelagem*: Implementação de um modelo de Regressão Linear e validação cruzada com 10 folds.
- *Visualização*: Exibição da distribuição dos erros de validação cruzada por meio de histogramas.

## Tecnologias Utilizadas
- *Python 3.x*
- *Bibliotecas*:
  - pandas para manipulação de dados
  - scikit-learn para modelagem e validação
  - matplotlib para visualização de dados
  - numpy para operações numéricas

## Instalação
Certifique-se de ter o Python 3.x instalado. Clone este repositório e instale as dependências necessárias:

```bash
git clone https://github.com/almeidatarcisio/Projeto-Unidade-9
cd instagram-engagement-analysis
pip install -r requirements.txt