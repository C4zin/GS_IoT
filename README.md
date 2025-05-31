
## Integrantes

Angello Turano RM: 556511

Cauã Sanches RM:558317

Leonardo Bianchi RM:558576




🔥 Previsão de Risco de Queimadas com IoT & Machine Learning
Um sistema inteligente para antecipar e mitigar o risco de queimadas por meio da coleta de dados ambientais e análise preditiva com IA.

📌 Visão Geral
Este projeto integra sensores IoT simulados e algoritmos de Machine Learning para prever o risco de queimadas com base em variáveis ambientais como:

🌡️ Temperatura

💧 Umidade do ar

🌫️ Presença de fumaça

💨 Velocidade do vento

A partir desses dados, o sistema classifica o risco de queimada, permitindo ações preventivas e alertas em tempo real.

🧠 Tecnologias Utilizadas
Camada	Ferramenta/Plataforma
📡 Sensores IoT	(Simulados no notebook)
🧮 Machine Learning	Python, scikit-learn
📊 Visualização	Seaborn, Matplotlib
☁️ Execução	Google Colab
📁 Dados	Geração sintética via NumPy

🛠️ Funcionalidades
✅ Geração de dados ambientais simulados

✅ Exploração dos dados e análise estatística

✅ Treinamento do modelo preditivo (Random Forest)

✅ Avaliação com métricas de acurácia, matriz de confusão e validação cruzada

✅ Identificação das variáveis mais influentes

📂 Estrutura do Projeto
bash
Copiar
Editar
📁 previsao-queimadas/
├── modelo_previsao_queimadas.ipynb  # Código completo do projeto
├── dados_simulados.csv              # (Opcional) Dados simulados
├── relatorio_tecnico.pdf            # Documento com metodologia e conclusões
└── README.md                        # Este arquivo

▶️ Como Executar
Acesse o arquivo modelo_previsao_queimadas.ipynb no Google Colab ou Jupyter Notebook.

Execute todas as células do notebook.

Visualize os gráficos e análises geradas ao final da execução.

Consulte o relatorio_tecnico.pdf para interpretação dos resultados.

📊 Modelo Utilizado: Random Forest
O algoritmo Random Forest foi escolhido por:

🌲 Alta acurácia com poucos ajustes;

🛡️ Resistência a overfitting;

💬 Boa interpretabilidade das variáveis;

📈 Ótimo desempenho com dados multivariados e não lineares.

