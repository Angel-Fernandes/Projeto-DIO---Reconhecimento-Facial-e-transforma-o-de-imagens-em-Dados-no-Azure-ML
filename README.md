# Projeto-DIO---Reconhecimento-Facial-e-transforma-o-de-imagens-em-Dados-no-Azure-ML

Passo a passo do projeto Reconhecimento Facial e Transformação ded imagens em Dados no Azure ML da DIO.

Links importantes:

[Detectar rostos no Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/02-content-safety.html(https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html))

[Ler texto no Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html(https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html))

[Analisar imagens no Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html(https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)(https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html))

Seguindo o passo a passo da documentação:

## Teste 1: Criando recurso e detectando rosto

Primeiro precisei criar um recurso de Machine Learning. 
Cliquei em "Criar recurso" 
![Img](/01.png)

e depois pesquisei por Azure Machine Learning no marketplace. 
![Img](/02.png)

Após encontrar o recurso, crie ele.

![Img](/03.png)

## Passo 2: Configurando o recurso do Azure Machine Learning

Na aba de Noções básica, Detalhes do recurso, informei a assinatura para cobrança no campo Assinatura e depois informei o Grupo de recursos que foi criado.

Após, em Detalhes da área de trabalho, é informei os detalhes do workspace que será criado. 
Criei o recurso clicando em Consultar + criar. Após a validação ser aprovada, cliquei em "Criar".
Após o recurso ser criado, cliquei no botão "Ir para o recurso" para acessar a página do recurso.
Nessa página, existe o botão "Iniciar o estúdio" que redirecionará para o estúdio do Azure Machine Learning.

![Img](/04.png)

## Passo 3 - Criando o modelo

No estúdio, na página do workspace criado anteriormente, acessei a opção do menu ML automatizado e na página aberto, cliquei em "Novo trabalho de ML automatizado".

![Img](/05.png)

Segui a documentação completa para preencher
 [https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html]

![Img](/06.png)

Ao final do preenchimento de todas as etapas, enviei o trabalho de treinamento e aguardei a conclusão.
Após a conclusão do aprendizado de máquina pude observar o resumo do modelo.

![Img](/07.png)

E acessei a lista de modelos

![Img](/08.png)


## Passo 4: Métricas do modelo

Para acessar as métricas do modelo treinado, na página do modelo, acesso o link informado em "Criado por trabalho". Também é possível acessar o trabalho informado na opção do menu "Tarefas (jobs)".

Na página da tarefa, acessei a aba métricas.

![Img](/09.png)
![Img](/10.png)

## Passo 5: Teste do modelo

Na página do modelo, acessei a aba "Pontos de extremidade" 

![Img](/11.png)

Cliquei em "predict-rentals" e em seguida em "testar"

![Img](/12.png)
