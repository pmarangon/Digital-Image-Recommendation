# Digital-Image-Recommendation
# Sistema de Recomendação por Imagens Digitais

Este projeto tem como objetivo desenvolver um **sistema de recomendação baseado em imagens**, que sugere produtos similares a partir de suas características visuais, como formato, cor e textura. O modelo utiliza **Deep Learning** para extrair características de imagens e recomendar produtos com aparência similar, sem depender de dados textuais como preço ou marca.

## Tecnologias Utilizadas
- **Python**
- **TensorFlow** e **Keras** para treinamento do modelo de deep learning
- **Matplotlib** para visualização
- **Google Colab** para execução do código e treinamento do modelo

## Como Funciona
1. O sistema carrega imagens de produtos (como bolsas e relógios) e as pré-processa.
2. Utilizando redes neurais convolucionais (CNN), o modelo aprende a identificar características visuais dos produtos.
3. Quando uma imagem é fornecida, o sistema retorna outras imagens com características visuais semelhantes, baseando-se no conteúdo das imagens, não em suas descrições textuais.

Link do Notebook
Acesse o notebook completo e execute os passos para testar o sistema de recomendação:

https://colab.research.google.com/drive/1S5HQ1213_ehbfEaH3z_Whqt7ryudUsD8?usp=sharing

Desenvolvimento
Este projeto foi desenvolvido com base no conhecimento adquirido durante o bootcamp Bairesdev na DIO (Digital Innovation One), onde aprendi sobre Deep Learning, Python, e desenvolvimento de sistemas de recomendação.
