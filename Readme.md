# Previsão de Nota de Crédito

## Descrição
Este projeto tem como objetivo desenvolver um modelo de machine learning capaz de prever a nota de crédito de clientes de uma financeira. Utilizando Python e algoritmos de aprendizado de máquina, o modelo analisa as características dos clientes para gerar uma previsão com precisão de 80%.

## Tecnologias Utilizadas
* **Python:** Linguagem de programação principal (versão 3.13.1).
* **Bibliotecas:**
    * Scikit-learn: Para construção e treinamento dos modelos de machine learning.
    * Pandas: Para manipulação e análise dos dados.
    * (todas as bibliotecas utilizadas estão presentes no arquivo requirements.txt)... ([text](../../requirements.txt))

## Pré-processamento: Apresentação dos passos para a resolução do projeto
* Passo a passo Passo 0 - Entender a empresa e o desafio da empresa
* Passo 1 - Importar a Base de Dados
* Passo 2 - Preparar a Base de Dados para a Inteligência Artificial
* Passo 3 - Treinar a Inteligência Artificial -> Criar o modelo: Nota de crédito: ruim,ok,boa
* Passo 4 - Escolher o melhor modelo
* Passo 5 - Usar o melhor modelo para fazer previsão de novos clientes

## Modelo
* **Algoritmo:** (Random Forest & KNeighborsClassifier (KNN))

* **Treino & Avaliação:** Métricas de avaliação utilizadas:
  * Criar a IA
     * modelo_arvoredecisao = RandomForestClassifier()
     * modelo_knn = KNeighborsClassifier()
   * Treinar a IA
     * modelo_arvoredecisao.fit(x_treino, y_treino)
     * modelo_knn.fit(x_treino, y_treino)


## Resultados
* **Precisão:** 80% (ou a precisão obtida)

## Autores
* (Marcelo Santos) - Hashtag treinamentis

## Como Executar
1. **Requisitos:** Requirements.txt: ([text](../../requirements.txt))
2. **Clonagem do Repositório:**
 ```bash
   git clone:https://github.com/oMarcelosantos/Previsao-IA.git



