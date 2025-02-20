<p align="left">
  <img src="https://img.shields.io/static/v1?label=Tipo&message=Desafio&color=8257E5&labelColor=000000" alt="Desafio" />
</p>

## Language
- [Versão em Português do conteúdo do README](README.md) <br/>
- [English version of the README content](README.us.md)
---
  
# Projeto de Transfer Learning em Python

Este projeto aplica a técnica de **Transfer Learning** em uma rede neural profunda para classificação de imagens. O exemplo utiliza o dataset **Cats vs Dogs**, mas o código pode ser adaptado para qualquer outro dataset de duas classes.

## Descrição do Projeto

O objetivo deste projeto é demonstrar como utilizar Transfer Learning para classificar imagens de gatos e cachorros. Utilizamos um modelo pré-treinado (**MobileNetV2**) e o adaptamos para a tarefa específica de classificação binária.

### Dataset

O dataset utilizado é o **Cats vs Dogs**, que contém imagens de gatos e cachorros. Ele pode ser baixado diretamente do [TensorFlow Datasets](https://www.tensorflow.org/datasets/catalog/cats_vs_dogs) ou do [Microsoft Research](https://www.microsoft.com/en-us/download/details.aspx?id=54765).

### Técnicas Utilizadas

- **Transfer Learning**: Foi utilizado o modelo MobileNetV2 pré-treinado no ImageNet.
- **Data Augmentation**: Para aumentar a diversidade do dataset e evitar overfitting.
- **Fine-Tuning**: Após o treinamento inicial, ajustamos algumas camadas do modelo para melhorar a acurácia.

## O Projeto

### Pré-requisitos

- Python 3.x
- Google Colab ou Jupyter Notebook
- Bibliotecas: TensorFlow, TensorFlow Datasets, Matplotlib, Numpy, Pillow

---

### Resultados

O modelo alcançou uma acurácia de **~98%** no conjunto de validação após o treinamento. Abaixo estão alguns exemplos de previsões:

| Imagem | Previsão |
|--------|----------|
| ![Gato]() | Gato com 99% de confiança |
| ![Cachorro]() | Cachorro com 97% de confiança |

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

### Links Úteis

- [Documentação do TensorFlow](https://www.tensorflow.org/)
- [TensorFlow Datasets](https://www.tensorflow.org/datasets)
- [Google Colab](https://colab.research.google.com/)
