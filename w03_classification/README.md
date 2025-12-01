## Неделя 3 — Классификация текста

Лекция 3: Классификация текстов и нейросетевые архитектуры

Лекция систематизирует подходы к классификации текстов, сравнивая классические алгоритмы (Naive Bayes, SVM, LogReg) и нейросетевые методы. Обсуждаются постановки задач (бинарная, многоклассовая, multi-label) и функции активации, а также детально разбирается архитектура сверточных (CNN) и рекуррентных (RNN) нейронных сетей для создания векторных представлений текстов.

Семинар 3: Регрессия по тексту (Salary Prediction)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/AlbinaBurlova/hse-bda-nlp-course/blob/main/w03_classification/sem3_cnn_for_text.ipynb
)

На семинаре решается задача регрессии - предсказание зарплаты по описанию вакансии с использованием гибридной нейросети на PyTorch. Студенты реализуют CNN-энкодеры для обработки текста поверх предобученных эмбеддингов GloVe, а также изучают методы интерпретации модели через анализ вклада отдельных токенов в итоговое предсказание.

### Референсы и материалы 

* [Lena Voita's NLP Course Text Classification](https://lena-voita.github.io/nlp_course/text_classification.html)
* [YSDA Natural Language Processing course](https://github.com/yandexdataschool/nlp_course)
* [Speech and Language Processing (3rd ed. draft, SLP3)](https://web.stanford.edu/~jurafsky/slp3/)
* [Introduction to Information Retrieval](https://nlp.stanford.edu/IR-book) 
* [A Comparison of Event Models for Naive Bayes Text Classification](https://kamalnigam.com/papers/multinomial-aaaiws98.pdf) 
* [Support-Vector Networks](https://doi.org/10.1007/BF00994018)
* [Text Categorization with Support Vector Machines (Learning with Many Relevant Features)](https://www.cs.cornell.edu/people/tj/publications/joachims_98a.pdf)
* [Convolutional Neural Networks for Sentence Classification](https://arxiv.org/abs/1408.5882)
* [Naive Bayes, Text Classification, and Sentiment](https://web.stanford.edu/~jurafsky/slp3/B.pdf)
* [Question Classification using Support Vector Machines](https://www.comp.nus.edu.sg/~leews/publications/p31189-zhang.pdf)
* [Convolution arithmetic](https://github.com/vdumoulin/conv_arithmetic)
