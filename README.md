# Projeto Final

**IFPB - Instituto de Educação e Ciência da Paraíba**

**Curso:** Sistemas para Internet</br>
**Disciplina:** Tópicos Especiais</br>
**Período:** 6°</br>
**Prof.:** Thiago Moura</br>

## Objetivo

Comparar os resultados de algoritmos de Machine Learning com problemas de classificação. Escolher dois problemas de classificação (bases) de um dos seguintes repositórios:

* **UCI:** [https://archive.ics.uci.edu/](https://archive.ics.uci.edu/)
* **Kaggle:** [https://www.kaggle.com/](https://www.kaggle.com/)

## Pré-Processamento

* Transformar todos os atributos para numérico
* Transformar os labels em numérico
* Normalizar os atributos na escala 0..1

## Algoritmos a serem utilizados

* Árvore de Decisão (gini e entropy)
* KNN (k igual a 5 e 10)
* MLP (escolher duas arquiteturas diferentes e variar o parâmetro `activation = {'relu', 'tanh'}`). "relu" é o valor default para o parâmetro `activation`.
* K-Means (K igual ao número de classes existente no problema)

**Total de modelos a serem executados e comparados:** 9 (nove)

## Protocolo Experimental

Executar um k-fold cross-validation (k = 10), com 90% dos dados para Treinamento e o restante para Teste.

Cada uma das divisões dos conjuntos deve ser utilizado para treinar cada algoritmo.

## Relatório

* **Para as MLPs:** Gerar gráfico mostrando a taxa de erro de treinamento em cada época.
* **Tabela:** Com as taxas de erro/acerto, que será a média dos 10 folds de teste, para cada algoritmo treinado. Exibir os valores em percentual.

## Observações

* Projeto em dupla
* **Entrega:** 11/03/2025