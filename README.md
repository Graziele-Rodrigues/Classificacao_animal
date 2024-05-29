# Introdução à Classificação com LinearSVC

Este repositório contém um código simples para introdução à classificação usando a biblioteca `scikit-learn` em Python. O objetivo deste código é treinar um modelo de classificação para distinguir entre porcos e cachorros com base em algumas características.

## Descrição do Código

O código realiza as seguintes etapas:

1. **Importação das Bibliotecas Necessárias**:
    - `LinearSVC` do `sklearn.svm` para criação do modelo de classificação.
    - `accuracy_score` do `sklearn.metrics` para avaliação do modelo.

2. **Definição das Features e Classes**:
    - Três características são consideradas para classificação:
        1. Pelo longo? (1 sim, 0 não)
        2. Perna curta? (1 sim, 0 não)
        3. Faz auau? (1 sim, 0 não)
    - São definidos três exemplos de porcos e três de cachorros com base nessas características.
    - As classes são representadas por `1` para porco e `0` para cachorro.

3. **Criação do Conjunto de Treinamento**:
    - Os dados de treinamento (`treino_x`) incluem as características dos porcos e cachorros.
    - As classes correspondentes (`treino_y`) são fornecidas como etiquetas.

4. **Treinamento do Modelo**:
    - Um modelo `LinearSVC` é instanciado e treinado com os dados de treinamento.

5. **Criação do Conjunto de Teste**:
    - São definidos três novos exemplos para teste.
    - As classes esperadas para o conjunto de teste são fornecidas.

6. **Predição e Avaliação do Modelo**:
    - O modelo faz previsões com base nos dados de teste.
    - A taxa de acerto das previsões é calculada usando `accuracy_score`.

## Instruções para Execução

1. Certifique-se de ter o `scikit-learn` instalado. Você pode instalá-lo usando o pip:
    ```bash
    pip install scikit-learn
    ```

2. Execute o código Python fornecido. Ele irá treinar o modelo e imprimir a taxa de acerto das previsões no console.

## Contribuição

Sinta-se à vontade para abrir issues ou enviar pull requests para melhorias neste código de introdução.

## Licença

Este projeto está licenciado sob a MIT License. Veja o arquivo LICENSE para mais detalhes.