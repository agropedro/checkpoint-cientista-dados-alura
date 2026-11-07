#  Checkpoint Cientista de Dados - Análise de Consumo de Café, Sono e Saúde

##  Objetivo do Projeto
Este projeto investiga a relação entre o consumo diário de cafeína, níveis de estresse, hábitos de estilo de vida e a qualidade do sono a partir de uma base global com **10.000 registros** (`synthetic_coffee_health_10000.csv`). Além da Análise Exploratória de Dados (EDA) e geração de insights de negócio, foi desenvolvido um pipeline de Machine Learning capaz de prever a qualidade do sono (`Sleep_Quality`) dos clientes com **99% de acurácia**.

##  Estrutura do Repositório
* `checkpoint_cientista_dados_coffee_health.ipynb`: Notebook principal contendo a EDA (Entrega #1), Visualizações e Insights (Entrega #2) e Modelagem Preditiva (Entrega #3).
* `synthetic_coffee_health_10000.csv`: Dataset bruto original.
* `coffee_health_processed.csv`: Dataset final pré-processado e com engenharia de atributos.
* `melhor_modelo_sleep_quality.pkl`: Modelo campeão serializado com `joblib`.

##  Tecnologias e Bibliotecas Necessárias
* **Python 3.8+**
* Bibliotecas: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `joblib`

##  Como Executar o Projeto
1. Clone este repositório:
   `git clone https://github.com/agropedro/checkpoint-cientista-dados-alura.git`
2. Instale as dependências no terminal:
   `pip install pandas numpy matplotlib seaborn scikit-learn joblib`
3. Abra e execute o arquivo `checkpoint_cientista_dados_coffee_health.ipynb` no **Google Colab** ou **Jupyter Notebook**.
