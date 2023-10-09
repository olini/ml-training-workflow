# ml-training-worflow
> Este projeto foi desenvolvido nas disciplinas Aprendizagem de Máquina I e II no Programa de Especialização em Software da Embraer em parceria com o CIn-UFPE, realizado em 2023

Repositório com workflow de treino e validação de modelos de machine learning para um problema de classificação multi-classe

**Estrutura de Arquivos:**
- .gitignore: lista de pastas e arquivos ignorados pelo controle de versionamento do repositório
- README.md: este arquivo de descrição do repositório
- Arquivo notebook_ml_training_worflow.ipynb: notebook com todo o pipeline de treinamento e validação de modelos
- pyproject.toml: arquivo com as dependências do projeto utilizado pelo gerenciador de dependências *poetry*
- poetry.lock: arquivo com as exatas versões utilizadas para cada uma das dependência do projeto utilizado pelo gerenciador de dependências *poetry*

**Banco de dados utilizado:** https://www.openml.org/search?type=data&status=active&id=45548&sort=runs

**Ferramentas e pacotes utilizados:**
- Gerenciador de dependências: poetry
- Virtualização de ambiente: python venv
- Manipulação de dados: pandas, numpy
- Visualização de dados: seaborn
- Testes de hipóteses: scipy
- Preparação de dados para modelagem: sklearn (StandardScaler, LabelBinarizer, VarianceThreshold, PCA) e imblearn (SMOTE)
- Workflow de modelagem: sklearn (StratifiedKFold para cross-validation e GridSearchCV para busca de hiper-parâmetros também com cross-validation - nested cross-validation)
- Modelagem: sklearn (GaussianNB, DecisionTreeClassifier, MLPClassifier, KNeighborsClassifier, RandomForestClassifier, LogisticRegression, Perceptron)
- Métricas de avaliação: sklearn (módulo metrics)

