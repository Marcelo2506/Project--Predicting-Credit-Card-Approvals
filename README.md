# Project: Predicting Credit Card Approvals
 Neste algoritmo o modelo irá avaliar se o cliente terá ou não crédito
 
![Credit card being held in hand](credit_card.jpg)

Os bancos comerciais recebem muitas solicitações de cartões de crédito. Muitas delas são rejeitadas por diversos motivos, como altos saldos de empréstimos, baixos níveis de renda ou muitas consultas no relatório de crédito de um indivíduo, por exemplo. Analisar essas solicitações manualmente é uma tarefa monótona, propensa a erros e demorada (e tempo é dinheiro!). Felizmente, essa tarefa pode ser automatizada com o poder do aprendizado de máquina, e praticamente todos os bancos comerciais já fazem isso atualmente. Neste projeto, você construirá um modelo preditivo automático para aprovação de cartões de crédito usando técnicas de aprendizado de máquina, assim como os bancos reais fazem.  

### Os Dados  
Os dados representam um pequeno subconjunto do conjunto de dados de Aprovação de Cartão de Crédito do **UCI Machine Learning Repository**, que contém informações sobre as solicitações de cartões de crédito recebidas por um banco. Este conjunto de dados foi carregado como um **DataFrame do pandas** chamado `cc_apps`. A última coluna do conjunto de dados representa o valor-alvo, ou seja, a variável que indica se o pedido foi aprovado ou não.  

### Tecnologias Utilizadas  
Para construir o modelo preditivo, utilizamos algumas bibliotecas fundamentais para análise de dados e aprendizado de máquina:  

- **Pandas**: Usado para carregar, manipular e analisar o conjunto de dados de forma eficiente. Ele permite a limpeza e a transformação dos dados para garantir que estejam prontos para o treinamento do modelo.  
- **NumPy**: Utilizado para operações matemáticas e manipulação de arrays numéricos, facilitando cálculos estatísticos e processamento eficiente de dados.  
- **Scikit-learn (sklearn)**: Biblioteca essencial para aprendizado de máquina, oferecendo ferramentas para pré-processamento de dados, construção de modelos, treinamento, avaliação de desempenho e ajuste fino dos hiperparâmetros.  

### Importância do Projeto e das Tecnologias  
A automação do processo de aprovação de crédito traz diversas vantagens tanto para os bancos quanto para os clientes:  
- **Eficiência e Rapidez**: Reduz o tempo necessário para analisar uma solicitação de crédito, permitindo que os clientes recebam respostas mais rapidamente.  
- **Redução de Erros Humanos**: A decisão automatizada diminui a subjetividade e inconsistências na avaliação das solicitações.  
- **Tomada de Decisão Baseada em Dados**: O aprendizado de máquina pode identificar padrões complexos nos dados que um analista humano pode não perceber, resultando em decisões mais precisas.  
- **Escalabilidade**: O modelo pode processar um grande volume de solicitações simultaneamente, tornando o sistema mais eficiente conforme a demanda aumenta.  

Este projeto demonstra a aplicação prática do aprendizado de máquina na indústria financeira e como o uso de bibliotecas poderosas como Pandas, NumPy e Scikit-learn pode transformar processos complexos em soluções inteligentes e automatizadas.

-----------------------------------------------------------------------------------------------------------------------

EN

Commercial banks receive many credit card applications. Many of them get rejected for various reasons, such as high loan balances, low income levels, or too many inquiries on an individual's credit report. Manually analyzing these applications is a tedious, error-prone, and time-consuming task (and time is money!). Fortunately, this process can be automated with the power of machine learning, and nearly every commercial bank does so nowadays. In this project, you will build an automatic credit card approval predictor using machine learning techniques, just like real banks do.  

### **The Data**  
The dataset represents a small subset of the **Credit Card Approval dataset** from the **UCI Machine Learning Repository**, which contains information on credit card applications received by a bank. This dataset has been loaded as a **pandas DataFrame** called `cc_apps`. The last column in the dataset is the target variable, which indicates whether the application was approved or not.  

### **Technologies Used**  
To build the predictive model, we utilize some essential libraries for data analysis and machine learning:  

- **Pandas**: Used to load, manipulate, and analyze the dataset efficiently. It allows for data cleaning and transformation to ensure the data is ready for model training.  
- **NumPy**: Utilized for mathematical operations and numerical array manipulation, facilitating statistical calculations and efficient data processing.  
- **Scikit-learn (sklearn)**: A key machine learning library that provides tools for data preprocessing, model building, training, performance evaluation, and hyperparameter tuning.  

### **Importance of the Project and Technologies**  
Automating the credit approval process brings several benefits for both banks and customers:  

- **Efficiency and Speed**: Reduces the time required to analyze a credit application, allowing customers to receive responses faster.  
- **Reduction of Human Errors**: Automated decision-making minimizes subjectivity and inconsistencies in the evaluation process.  
- **Data-Driven Decision Making**: Machine learning can identify complex patterns in data that a human analyst may overlook, leading to more accurate decisions.  
- **Scalability**: The model can process a large volume of applications simultaneously, making the system more efficient as demand increases.  

This project demonstrates the practical application of machine learning in the financial industry and how powerful libraries like **Pandas, NumPy, and Scikit-learn** can transform complex processes into intelligent, automated solutions.
