 Projeto Python IA: Inteligência Artificial e Previsões

 Case: Score de Crédito dos Clientes

Você foi contratado por um banco para conseguir definir o score de crédito dos clientes. Necessário analisar todos os clientes do banco e, com base nessa análise, criar um modelo que consiga ler as informações do cliente e dizer automaticamente o score de crédito dele: Ruim, Ok, Bom
Isso vai definir se o banco vai emprestar dinheiro, se ele vai ter crédito entre outros benefícios dentro do banco. Então o
objetivo é fazer um tratamento na base de dados e criar alguns algoritmos de classificação e verificar qual deles é o melhor.
Com isso conseguir fazer uma previsão dos clientes para saber se ele vai ser um cliente com um bom score ou não

Os passos são:
• Importar a base de dados
• Verificar informações vazias
• Fazer o tratamento na base de dados
• Selecionar as colunas de treino para o modelo
• Treinar 2 modelos
• Verificar o melhor modelo
• Verificar quais as características mais importantes para definir o score do cliente

Bibliotecas utilizadas: Pandas, Sklearn(codificador LabeEncoded)
Modelos utilizados:
- RandomForestClassifier  (https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html#sklearn-neighbors-kneighborsclassifier)
- KNeighborsClassifier  (https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html#sklearn.ensemble.RandomForestClassifier)
