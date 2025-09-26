
# Projeto da Pós Graduação em Machine Learning

💻 MVP Sprint: Machine Learning & Analytics
Este projeto de Machine Learning foca na construção de um modelo preditivo de classificação supervisionada para analisar e prever a sobrevida de pacientes com câncer de pulmão.

O objetivo é identificar padrões, determinar fatores de risco e aprimorar as estratégias de detecção precoce e tratamento.

📊 Dados e Metodologia
Dataset: Utilizamos um conjunto de dados abrangente sobre mortalidade por câncer de pulmão, contendo 222.684 instâncias.

Foco da Análise: A investigação se concentrou em hipóteses sobre a correlação entre fatores biométricos (IMC, colesterol, hipertensão) e sobrevida, além da análise de grupos de risco por idade.

Pré-processamento: O pipeline de dados incluiu limpeza, pré-processamento e o uso da técnica SMOTE para lidar com o desbalanceamento de classes.

Modelo Principal:  CART (Classification and Regression Tree) como a melhor opção é clara e estratégica.

🎯 Resultados e Otimização
Performance: O modelo alcançou um Recall de 92%. Este resultado prioriza a classe minoritária ("Sobreviveu").

Trade-off: O alto Recall foi obtido com o custo de uma baixa Precision (22%).

⏭️ Próximos Passos
Para encontrar um melhor equilíbrio entre métricas, sugere-se:

Ajustar o Limiar de Decisão do modelo.

Explorar modelos mais robustos, como Gradient Boosting ou XGBoost.

Ajustar a estratégia de sampling do SMOTE.


