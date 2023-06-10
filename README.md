# IA para identificar boto-cor-de-rosa por imagens 
Projeto em ia para o processamento de imagens com o objetivo de identificar imagens do boto-cor-de-rosa

### Bibliotecas utilizadas
- TensorFlow
- Keras
- Matplotlib
- Numpy
- OpenCV

## Objetivo 
Em conjunto em com a [Beca Alvarez](https://github.com/BecaAlvarez) pensamos em alguma forma de poder auxiliar pesquisadores no combate a extinção da especie do boto-cor-de-rosa. Desse modo, discutimos sobre como, em nosso meio de estudo, poderias auxiliar essas pessoas no monitoramento da especie em questão.

Dentre os principais pontos levados em consideração, decidimos aproveitar a matéria de Projeto de Engenharia III - que tivemos durante o 7 semestre da faculdade- para desenvolve um modelo de rede neural para identificar por meio de imagens a especie do boto-cor-de-rosa.

## Sobre o código 
Utilizando a plataforma Google Colaboratory, desenvolvemos um código para a analise de imagens e apos o processamento informar se a imagem seria ou não de um boto. 

Basicamente temos duas pastas contendo as imagens positivas(referentes ao boto-cor-de-rosa) e outra das imagens negativas(referentes a outras especies comuns na Amazônia). No código, conforme as pastas, temos as classes 0 para as imagens positivas e 1 para as imagens negativas.

![classe](https://github.com/NathanSFon/Boto_Processamento_de_imagens/blob/main/Screeshots/Classes.png)

Realizamos todo o processamento da rede neura e ao final, com o modelo treinado, pegamos uma das imagens e passamos para a analise do modelo que informa por uma porcentagem se a imagem é ou não é de um boto. 

![modelo](https://github.com/NathanSFon/Boto_Processamento_de_imagens/blob/main/Screeshots/modelo.png)
![Treinamento](https://github.com/NathanSFon/Boto_Processamento_de_imagens/blob/main/Screeshots/treinamento.png)

![Resultado](https://github.com/NathanSFon/Boto_Processamento_de_imagens/blob/main/Screeshots/resultado.png)

Segue o link do notebook onde desenvolvemos o código [boto_ia](https://colab.research.google.com/drive/1lieqv3eAjLTHn6RNGW2laqEFHoIZ6znb#scrollTo=yZrJpThKa00D). Voce pode acessar e fazer seus testes. 
O banco de imagens que utilizamos estão aqui [Banco de imagens](https://github.com/BecaAlvarez/RedeNeural_BotoCorDeRosa). 

