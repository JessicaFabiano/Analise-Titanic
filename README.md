# 🚢 Previsão de Sobrevivência no Titanic - Machine Learning

## Sobre o Projeto
Este projeto é uma análise de dados e aplicação de Machine Learning utilizando o famoso dataset do Titanic. O objetivo principal é construir um modelo preditivo capaz de determinar se um passageiro sobreviveria ou não ao naufrágio, com base em suas características (idade, sexo, classe social, etc.).

## Objetivos
- Realizar a Análise Exploratória de Dados (EDA).
- Tratar dados faltantes e transformar variáveis categóricas em numéricas (Feature Engineering).
- Treinar e avaliar um modelo de Machine Learning (`RandomForestClassifier`).
- Visualizar as variáveis que mais influenciaram na sobrevivência.

## Tecnologias e Bibliotecas Utilizadas
- **Python**
- **Pandas** para manipulação e análise de dados.
- **Seaborn** e **Matplotlib** para visualização de dados.
- **Scikit-Learn** para o modelo de Machine Learning.

## Etapas do Desenvolvimento
1. **Carregamento e Exploração:** Leitura dos dados de treino e teste e verificação das taxas de sobrevivência por sexo e classe.
2. **Limpeza de Dados:** Identificação de valores nulos (visualizados via mapa de calor).
3. **Feature Engineering:** * Extração de "Títulos" (Mr., Miss., Mrs., etc.) a partir dos nomes dos passageiros para estimar de forma mais precisa as idades faltantes.
   * Preenchimento de valores nulos nas colunas `Age`, `Embarked` e `Fare`.
4. **Transformação:** Conversão de variáveis categóricas (Sexo, Porto de Embarque, Títulos) em formato numérico.
5. **Modelagem:** Descarte de colunas não preditivas (ID, Nome, Ticket, Cabine) e treinamento de um modelo `Random Forest` com 100 árvores.
6. **Avaliação e Resultados:** Geração de gráficos demonstrando a importância de cada variável (Sendo 'Sex' e 'Title' as mais relevantes) e a proporção de sobreviventes nos dados de teste.

## Como executar
1. Clone este repositório.
2. Certifique-se de ter os arquivos `train.csv` e `test.csv` no mesmo diretório.
3. Execute o notebook `Titanic.ipynb` em um ambiente Jupyter ou Google Colab.




