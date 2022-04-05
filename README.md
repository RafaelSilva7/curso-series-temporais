# Análise de Séries Temporais e Alinhamento Não-Linear com Dynamic Time Warping (DTW)


Este repositório contém apresentações (slides) e código (notebooks) do curso ministrado na Petrobras, em decorrência da parceria com a UFSCar. 

O curso tem como objetio instroduzir conceitos de mineração de dados em séries temporais utilizando técnicas clássicas de aprendizado de máquina como árvores de decisão e clustering. Na segunda metade do curso aborda-se técnicas específicas de séries temporais como alinhamento não-linear com Dynamic Time Warping (DTW). 


## Conteúdo do curso
---


A seguir esta listado todas as aulas apresentadas ao longo do curso, juntamente com seus respectivos notebooks.

- **Aula 1:** Introdução e pré-processamento
    - Filtros Classicos.ipynb
- **Aula 2:** Componentes de uma série temporal e Forecasting
    - Decomposicao serie temporal.ipynb
    - Forecast.ipynb
- **Aula 3:** Medidas de distância, classificação e regressão extrínseca
    - Busca Euclidiana.ipynb
    - Classificação com sktime.ipynb
    - Classificação com tsfel.ipynb
    - Classificação com Arvore de Decisão.ipynb
    - Clustering.ipynb
- **Aula 4:** Tarefas de Mineração por Similaridade
- **Aula 5:** Mais tarefas de mineração por similaridade e o Matrix Profile (MP)
    - Matrix Profile com Stumpy.ipynb
    - Segmentação.ipynb
- **Aula 6:** Dynamic Time Warping
    - DTW com DTAIDistance.ipynb
    - DTW com dtwalign.ipynb
    - UCR Suite.ipynb
- **Aula 7:** DTW - Invariâncias
- **Aula 08:** DTW - Busca
    - UCR Suite.ipynb
- **Aula 09:** DTW - Variações
    - Variações DTW.ipynb


## Instalação de depências
---

Os exemplos práticos apresentados no curso foram todos desenvolvido e executados no google colab. Caso deseje executá-los em sua maquina local utilizando o anaconda e o jupyter, a fim de evitar problemas de compatibilidade, siga os seguintes passo para configuração do ambiente:

Com o anaconda já instalado crie um novo ambiente python dentro de uma pasta qualquer
``` 
$ conda create -n curso_dtw python=3.7.13
$ conda activate curso_dtw
```

Instale as bibliotecas que serão utilizadas durante o curso
```
$ conda install scipy statsmodels stumpy plotly jupyter
$ conda install --c conda-forge dtaidistance sktime
$ pip install dtwalign tsfel
```

Por fim basta iniciar seu ambiente jupyter
```
$ jupyter notebook
```


## Autores
--- 

[Dr. Diego Furtado Silva](https://github.com/diegofurts) - Apresentador

[Luiz Antonio Rozedo](https://github.com/luizantonio26) - Assistente

[Rafael da Costa Silva](https://github.com/RafaelSilva7) - Assistente
