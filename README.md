<div align="center">
  
  <img src="https://img.freepik.com/vetores-gratis/ilustracao-do-mes-de-conscientizacao-do-cancer-de-mama-plana_23-2149680731.jpg" alt="Ilustração do Mês de Conscientização do Câncer de Mama" width="40%">

  Imagem de <a href="https://br.freepik.com/vetores-gratis/ilustracao-do-mes-de-conscientizacao-do-cancer-de-mama-plana_31693124.htm#from_view=detail_collection">Freepik</a>

</div>

# Projeto de Previsão de Câncer de Mama

# Visão Geral do Projeto
Este projeto tem como objetivo abordar o desafio de prever com precisão o diagnóstico de câncer de mama em pacientes, com base em dados coletados no conjunto de dados de diagnóstico de câncer de mama do Wisconsin. Este conjunto de dados contém informações clínicas e características de tumores mamários, tornando-o um recurso valioso para a construção de modelos de aprendizado de máquina para auxiliar no diagnóstico médico.

Através da análise detalhada dos dados, engenharia de recursos e a implementação de modelos de classificação de aprendizado de máquina, nosso objetivo é desenvolver um sistema eficaz que possa identificar padrões e características que ajudem a distinguir tumores malignos de tumores benignos, proporcionando aos médicos e profissionais de saúde uma ferramenta adicional para a tomada de decisões.

# Ferramentas
* Linguagem de programação: [Python](https://www.python.org/)
* IDE: [Colab](https://colab.research.google.com/)
* Ferramentas Estatísticas: Métodos Estatísticos e Análise Exploratória de Dados
* Modelos de Classificação: [Logistic Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html) , [Random Forest Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html ) e [Decision Tree Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)

# Instalação
Este projeto usa as seguintes bibliotecas Python na versão 3.10 do Python:

__pandas, numpy, seaborn, matplotlib.pyplot, sklearn.preprocessing, sklearn.linear_model, sklearn.model_selection, sklearn.metrics, sklearn.tree, sklearn.ensemble, pickle__

Clone este repositório em sua máquina local usando $ git clone https://github.com/RaonyGauto/Breast-Cancer-Wisconsin--Diagnostic-

# Conjunto de Dados
Os dados utilizados neste projeto foram retirados a partir do site [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data). O dataset contém informações sobre características de núcleos celulares a partir de amostras retiradas através de biopsia do tecido mamário. Os atributos incluem medidas de textura, perímetro, área, suavidade, entre outros, que são usados para prever se um tumor é maligno ou benigno.

# Análise Exploratória dos Dados
O projeto começa com uma análise exploratória dos dados para entender a distribuição das características, identificar possíveis correlações e visualizar a diferença entre tumores malignos e benignos. Isso ajuda na seleção de recursos relevantes para a construção dos modelos de aprendizado de máquina.

# Preparação dos Dados
Nesta etapa, os dados são preparados para treinamento dos modelos. Isso inclui a divisão dos dados em conjuntos de treinamento e teste, bem como a normalização das características para o modelo ter melhor processamento dos dados.

# Treinamento e Avaliação do Modelo
São treinados vários modelos de classificação, Logistic Regression, Decision Tree e Random Forest, para prever qual a classe do tumor, maligno ou benigno. Os modelos são avaliados usando métricas de desempenho, como acurácia, recall, pontuação F1 e classification report e matriz de confusão. O objetivo é escolher o modelo com o melhor desempenho.

# Resultados e Conclusões
Os resultados finais incluem a avaliação do modelo escolhido e suas métricas de desempenho. Também são apresentadas interpretações clínicas das características mais importantes para o diagnóstico, além de discussões sobre a importância do projeto na medicina e na tomada de decisões clínicas.

# Contribuição
Este projeto é aberto a contribuições e sugestões. Se você tiver ideias para melhorar o projeto, novas técnicas de modelagem ou melhorias na análise de dados, sinta-se à vontade para enviar um pull request ou abrir uma issue. Estamos ansiosos para colaborar e melhorar o diagnóstico de câncer de mama.
