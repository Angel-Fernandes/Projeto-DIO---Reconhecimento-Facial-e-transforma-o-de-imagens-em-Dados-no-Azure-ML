# Projeto DIO- Reconhecimento Facial e transformação de imagens em Dados no Azure ML

Passo a passo do projeto Reconhecimento Facial e Transformação ded imagens em Dados no Azure ML da DIO.

Links importantes:

[Detectar rostos no Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/02-content-safety.html(https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html))

[Ler texto no Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html(https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html))

[Analisar imagens no Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html(https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)(https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html))

Seguindo o passo a passo da documentação:

## Teste 1: Criando recurso e detectando rosto

Abri o portal Azure  e cliquei em "Create a resourse"

![Img](inputs/01.png)

Em seguida em "categorias" cliquei na opção "IA + Machine Learning"
![Img](inputs/02.png)

Pesquisei por "Azure AI services" e cliquei em create, seguindo a documentação.

![Img](inputs/03.png)

Ao criar abri o Vision Studio ([azure.com](https://portal.vision.cognitive.azure.com/gallery/featured))

![Img](inputs/04.png)

Alterei o theme para dark e cliquei em "View all resources" e selecionei o recurso criado "LabRF-TI"  (escolhi esse nome em referência ao nome do laboratório do curso "Reconhecimento Facial e transformação de imagens em Dados no Azure ML") e selecione como "default" e cliquei no x.
![image](inputs/05.png)

Ao clicar no "x" voltei para a página inicial e cliquei em "face"

![image](inputs/06.png)

Cliquei em "Detect faces in na image" e selecionei o "Try it out"

![image](inputs/07.png)

Selecionei uma imagem e o rosto da pessoa foi detectado em seguida, com o atributo e o código em JSON

![image](inputs/08.png)

[Clique aqui para ver o código](output/DetectandoRosto.json)

## Teste 2: Análise de documentos
Para fazer análise de dados, voltei a página inicial e cliquei em "Optical character recognition" para fazer análise de caracteres.

![image](inputs/09.png)

Abrindo "Extract text from images"

![image](inputs/10.png)

A opção "Try it out" já estava marcada, então prossegui e selecionei uma imagem e atributo e o código em JSON foi detectado em seguida

![image](inputs/11.png)

[Clique aqui para ver o código](output/AnaliseDeDocumentos.json)

Logo abaixo apareceu próximas etapas

![image](inputs/12.png)

## Teste 3 - Análise de imagem
Voltando a página inicial, novamente, cliquei em image analysis

![image](inputs/13.png)

E escolhi a opção "Add dense captions to images"

![image](inputs/14.png)

Selecionando uma imagem, ele traz toda a descrição em atributos e o código JSON.
A descrição serve também como acessibilidade.



![image](inputs/15.png)

[Clique aqui para ver o código](output/AnaliseDeImagem.json)

Logo abaixo apareceu próximas etapas

![image](inputs/16.png)
