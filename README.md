# Conhecendo a biblioteca `CatBoost`

![image](https://user-images.githubusercontent.com/63373520/148584461-31fd3b4e-23f5-445e-9c91-05482de406b5.png)
- https://catboost.ai/


O _CatBoost_ é um framework utilizado em aplições de `Machine Learning` para lidar com dados categóricos.

**Curiosidade:** Esta biblioteca é a primeira tecnologia de aprendizado de máquina `Russa` de código aberto.

**O que é o _CatBoost_?**

`CatBoost` é um algoritmo para _aumento de gradiente_ em árvores de decisão. Ele é desenvolvido por pesquisadores e engenheiros da [**Yandex**](https://en.wikipedia.org/wiki/Yandex) e é usado para pesquisa, sistemas de recomendação, assistente pessoal, carros autônomos, previsão do tempo e muitas outras tarefas na Yandex e em outras empresas, incluindo **CERN**, **Cloudflare**, táxi **Careem**.<br><br>

**Outras curiosidades**

- pode ser integrado facilmente na estrutura de aprendizado profundo (`Deep Learning`), como o _TensorFlow_ do Google e o _Core ML_ da Apple. 
- pode trabalhar com diversos tipos de dados para ajudar a resolver uma ampla gama de problemas, é um dos que mais oferece a melhor precisão da classe _target_.
- o nome **CatBoost** vem de duas palavras "**Cat**egory" e "**Boost**ing".
- funciona muito bem como áudio, texto, imagem, incluindo dados históricos.
- `Boost` vem do algoritmo de aprendizado de máquina de aumento de gradiente. O aumento de gradiente é um algoritmo de aprendizado de máquina amplamente aplicado a vários tipos de desafios de negócios, como detecção de fraude, itens de recomendação, previsão e etc.
- pode retornar bons resultados com uma quantidade de dados relativamente pequeno, ao contrário dos modelos de _Deep Learning_ que precisam de uma grande base de dados.


**Vantagens da biblioteca:**
- `desempenho`: manipulaçao de recursos categóricos automaticamente. Podemos usa-lo sem a necessidade de quaisquer pré-processamento explícito para converter categórias em números.
 - converte valores categóricos em números usando várias estatísticas em combinações de recursos categóricos e numéricos.
- `robustez`: reduz a necessidade de ajuste extensivo de hiperparâmetros e diminui as chances de sobreajuste, o que leva a modelos mais generalizados. Pórem há alguns parâmetros que podemos ajustar, como o número de árvores, taxa de aprendizagem, regularização, profundidade da árvore e entre outros.

O **CatBoost** pode ser usado tanto para problemas de _classificação_ e de _regressão_.
- `classificação`: **CatBoostClassifier**.
- `regressão`: **CatBoostRegressor**.

A aplicação da biblioteca **não requer** a conversão do conjunto de dados em nenhum formato específico, como _XGBoost_ e _LigthGBM_.

Link do [notebook](https://colab.research.google.com/drive/1cBVxhR5hznKCL6KUTwbIOHCEpPb7y7NI#scrollTo=KN_7HB2gKycY).



