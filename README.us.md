<p align="left">
  <img src="https://img.shields.io/static/v1?label=Type&message=Challenge&color=8257E5&labelColor=000000" alt="Challenge" />
</p>

## Language
- [Versão em Português do conteúdo do README](README.md) <br/>
- [English version of the README content](README.us.md)




# Transfer Learning Project in Python

This project applies the **Transfer Learning** technique to a deep neural network for image classification. The example uses the **Cats vs Dogs** dataset, but the code can be adapted to any other two-class dataset.

## Project Description

The goal of this project is to demonstrate how to use Transfer Learning to classify images of cats and dogs. We use a pre-trained model (**MobileNetV2**) and adapt it for the specific task of binary classification.

### Dataset

The dataset used is **Cats vs Dogs**, which contains images of cats and dogs. It can be downloaded directly from [TensorFlow Datasets](https://www.tensorflow.org/datasets/catalog/cats_vs_dogs) or from [Microsoft Research](https://www.microsoft.com/en-us/download/details.aspx?id=54765).

### Techniques Used

- **Transfer Learning**: The MobileNetV2 model pre-trained on ImageNet was used.
- **Data Augmentation**: To increase dataset diversity and avoid overfitting.
- **Fine-Tuning**: After initial training, we fine-tuned some layers of the model to improve accuracy.

## The Project

### Prerequisites

- Python 3.x
- Google Colab or Jupyter Notebook
- Libraries: TensorFlow, TensorFlow Datasets, Matplotlib, Numpy, Pillow

---

### Results

The model achieved an accuracy of **~98%** on the validation set after training. Below are some examples of predictions:

| Image | Prediction |
|--------|----------|
| ![Cat](https://raw.githubusercontent.com/wekers/Transfer-Learning-Cats-Dogs/refs/heads/main/img/curled-600nw-1679659792.webp) | Cat with 99% confidence |
| ![Dog](https://raw.githubusercontent.com/wekers/Transfer-Learning-Cats-Dogs/refs/heads/main/img/Belgian_Groenendael_600.jpg) | Dog with 97% confidence |

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

### Useful Links

- [TensorFlow Documentation](https://www.tensorflow.org/)
- [TensorFlow Datasets](https://www.tensorflow.org/datasets)
- [Google Colab](https://colab.research.google.com/)
