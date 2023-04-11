# Pipline de dados
Pipline de ingestão de dados, ETL e apresentação ao usuário final (profissional de dados), utilizando multiplas tecnologias..

- Pré-processamento, análise, visualização, geração de insights, construção de dashboards. O projeto visa fornecer uma forma fácil e iterativa de visualizar informações diferentes (PIB, desemprego e inflação) a nível mundial.

  
Objetivo: Disponibilizar, em formato estrututrado, mensagens enviadas por participantes, em um grupo do Telegram, aplicando cloud computing para armazenamento e processamento de bases particionadas.


Fonte dos dados: 


1 - Dados foram obtidos:

  Para fins didáticos, os dados aqui utilizados são fictícios. Trata-se de um sistema que ainda não foi colocado em produção. Portanto, os dados não são válidos para embasar qualquer decisão.
  
## Tecnologias Utilizadas

  Telegram:
  
    - BotFhater - nativo do Telegram;

  Python:
  
    - para configuração do webhook;
    - escrever as funções lambda; e
    - pré-visualizar o formato em que o webook do Telegram envia as mensagens;

  Vários sistemas da AWS:

    - S3;
    - Lambda;
    - Athena;
    - EventBridge;
    - API Gateway;
    - IAM.

- Conceitos aplicados:

  * Programação orientada à objetos

  * Pré-processamento de dados

  * Cloud computing
  
  
  
## Funcionalidades

- O projeto foi conduzido para, ao final, proporcionar o acesso aos dodos (mensagens enviadas em um grupo do telegram, e seus metadados) em formato estruturado, possibilitando ao profissional de dados aplicar uma infinidade de técnicas, como agregação, sumarização e utilizar estes dados para modelos de machine learning.

## Visualizar

1 - Acesse clicando no arquivo acima com extensão '.ipynb', neste repositório;


2 - Faça o clone do repositório para participar deste projeto, ou

## Resultados

Após a implantação do projeto, podemos aplicar linguagem SQL, com o AWS Athena, e, utilizar os dados para responder à questões de negócio, por exemplo:

![image](https://user-images.githubusercontent.com/96034581/231176272-8cf9cf78-89a8-4744-bef7-3b37ca523e89.png)


## Conclusão

A construção de um pipline dados permitiu:

1 - A utilização comercial das mensagens, e metadados das mensagens. Com essas informações em mãos será possível validar insights das equipes responsáveis pelo marketing, vendas, custumer success, etc.

2 - Para implantar a arquitetura inicialmente apresentada, foram utilizadas várias tecnologias, dentre as quais:

BotFhater - nativo do Telegram;

Python - para configuração do webhook, escrever as funções lambda, e, pré-visualizar o formato em que o webook do Telegram envia as mensagens;

Vários sistemas da AWS:

S3
Lambda
Athena
EventBridge
API Gateway
IAM.
3 - Em algumas horas, utilizando recursos de cloud computing, você ou sua empresa já podem dispor de um dos recursos mais valiosos atualmente, os dados.
