## Неделя 2 — Векторные представления и тематическое моделирование

Лекция 2: Векторные представления (Embeddings) и Topic Modeling
Лекция знакомит с дистрибутивной семантикой и эволюцией методов векторизации: от счетных (LSA, PPMI) и гибридных (GloVe) до нейросетевых предсказательных моделей (Word2Vec: CBOW и Skip-gram). Разбираются техники эффективного обучения, такие как Negative Sampling, а также переход от уровня слов к уровню документов через тематическое моделирование с использованием латентного размещения Дирихле (LDA).

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github.com/AlbinaBurlova/hse-bda-nlp-course/blob/main/w02_embeddings_topics/sem02_embeddings.ipynb
)

Семинар 2: Векторные представления и LDA
На семинаре обучаются собственные эмбеддинги Word2Vec с помощью библиотеки `gensim` и сравниваются с предобученными векторами GloVe, также решается проблема отсутствующих слов (OOV) через FastText. Особое внимание уделяется визуализации семантических кластеров методами понижения размерности PCA и t-SNE. Практическая часть завершается построением тематической модели LDA для кластеризации документов и интерпретацией выделенных тем с помощью инструмента `pyLDAvis`.

### Референсы и материалы

- Mikolov et al., [Efficient Estimation of Word Representations in Vector Space (Word2Vec)](https://arxiv.org/abs/1301.3781)  
- Mikolov et al., [Linguistic Regularities in Continuous Space Word Representations](https://aclanthology.org/N13-1090.pdf)  
- Quote origin [You shall know a word by the company it keeps](https://quoteinvestigator.com/2022/09/18/word-company/)  
- Pennington et al., [GloVe: Global Vectors for Word Representation](https://arxiv.org/abs/1406.1078)  
- Deerwester et al., [Indexing by Latent Semantic Analysis](https://doi.org/10.1002/(SICI)1097-4571(199009)41:6%3C391::AID-ASI1%3E3.0.CO;2-9)  
- Blei et al., [Latent Dirichlet Allocation](http://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf)  
- Jurafsky & Martin, [Speech and Language Processing (SLP3): Pointwise Mutual Information (PMI)](https://web.stanford.edu/~jurafsky/slp3/J.pdf)
- [Word2Vec: a Prediction-Based Method (Lena Voita NLP Course)](https://lena-voita.github.io/nlp_course/word_embeddings.html#:~:text=Word2Vec%3A%20a%20Prediction%2DBased%20Method)
- [YSDA Natural Language Processing course](https://github.com/yandexdataschool/nlp_course)

Библиотеки и инструменты:

- [Gensim](https://radimrehurek.com/gensim/) - Topic modelling for humans (Word2Vec, FastText, GloVe loader).
- [scikit-learn](https://scikit-learn.org/) - PCA, t-SNE, LatentDirichletAllocation.
- [pyLDAvis](https://github.com/bmabey/pyLDAvis) - Интерактивная визуализация тем LDA.
- [Bokeh](https://bokeh.org/) - Библиотека для интерактивной визуализации. 
