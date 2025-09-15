# PROJETO PANDA
Desafio proposto para o grupo de Machine-Learning + Deep Learning grupo Panda UFSCar.

Projeto 1 – Machine Learning (Classificação)
📌 Descrição

Este projeto faz parte da disciplina de Machine Learning, referente às semanas 5 e 6.
O objetivo é aplicar técnicas de classificação supervisionada, comparando diferentes modelos e avaliando seus desempenhos no dataset Wine.

🎯 Objetivos

Escolher um dataset de classificação.

Treinar ao menos dois modelos vistos em aula (Regressão Logística e Random Forest).

Avaliar os modelos com métricas adequadas.

Explicar qual modelo teve melhor desempenho e por quê.

📊 Dataset

Nome: Wine Recognition Dataset

Fonte: sklearn.datasets.load_wine()

Descrição: O dataset contém 178 amostras de vinhos de 3 classes diferentes, descritas por 13 variáveis químicas (ex.: teor de álcool, acidez, fenóis, intensidade de cor).

Tarefa: Classificação multiclasse (3 classes).

🤖 Modelos Treinados

Regressão Logística

Random Forest (100 árvores)

| Métrica               | Regressão Logística | Random Forest |
| --------------------- | ------------------- | ------------- |
| **Acurácia**          | 0.981               | 1.000         |
| **Precisão (macro)**  | 0.982               | 1.000         |
| **Revocação (macro)** | 0.984               | 1.000         |
| **F1-score (macro)**  | 0.983               | 1.000         |

🔹 Matrizes de Confusão

Regressão Logística: 1 erro na classe 1

Random Forest: 100% de acertos

🔹 Importância das Variáveis (Random Forest)

Top 5 variáveis mais relevantes:

alcohol

color_intensity

flavanoids

proline

hue

📌 Conclusão

Os resultados mostram que ambos os modelos tiveram desempenho muito bom no dataset Wine, mas o Random Forest se destacou:

A Regressão Logística atingiu 98,1% de acurácia, apresentando apenas um erro de classificação.

O Random Forest obteve 100% de acurácia, classificando corretamente todas as instâncias de teste.

Além disso, o Random Forest permite analisar a importância das variáveis, mostrando que atributos como teor alcoólico, intensidade de cor e flavanoides são cruciais na classificação de vinhos.

➡️ Portanto, o Random Forest foi o modelo com melhor desempenho, devido à maior acurácia, robustez e interpretabilidade.

👥 Autores

João Victor de Mendonça Felizardo Silva

Dariush Tahzibi Santos
