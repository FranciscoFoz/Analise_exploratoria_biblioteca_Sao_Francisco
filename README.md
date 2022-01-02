# Sistema integrado das bibliotecas de São Francisco: Uma análise exploratória dos dados

<p align="center"> 
<img src="https://scontent.fcpq3-1.fna.fbcdn.net/v/t31.18172-8/171711_10150153741865609_7118011_o.jpg?_nc_cat=104&ccb=1-5&_nc_sid=174925&_nc_ohc=nrjm7CEB4KoAX-wp8mZ&_nc_oc=AQmfCEz0DIw1kRpFOvq7F1nqFJYmISjhsxxMH9_nXL7AlvgfEuyOQMLwR1BLPCj5Du18a6dhr4qm4ayh57s7qvLM&_nc_ht=scontent.fcpq3-1.fna&oh=00_AT9Q-nP7ImC2uIKUI-rWwB14i6es2TtgYsTJc12fy-ZBIw&oe=61E8A7B4" height="800" width="500"> ></a> 
</p>
Fonte: [Página do Facebook dos sistemas de bibliotecas](https://www.facebook.com/sfpl.org)


Elaborado por Francico Foz

<a href="https://img.shields.io/badge/author-gustavolq-blue.svg)](https://www.linkedin.com/in/francisco-tadeu-foz/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>  

---

Olá! 

Neste repositório você encontrará o projeto do meu [artigo]() 


## Resumo
A análise exploratória de dados é uma abordagem utilizada para se conhecer os dados a se trabalhar. 
A partir da limpeza, conhecimento das variáveis, resumos das principais características estatísticas e visualizações, pode-se responder algumas perguntas básicas e deixar o conjunto pronto para análises mais profundas.

Este projeto tem como objetivo principal realizar uma **análise exploratória** do conjunto de dados do sistema de bibliotecas de São Francisco. 

### Dataset

Encontrei esse conjuntos inicialmente no [Kaggle](https://www.kaggle.com/datasf/sf-library-usage-data?select=Library_Usage.csv), mas estarei utilizando os dados do [Portal de dados da cidade de São Francisco](https://data.sfgov.org/Culture-and-Recreation/Library-Usage/qzz6-2jup).

O conjunto de dados inclui aproximadamente 420.000 registros, com cada registro representando um usuário anônimo da biblioteca. As colunas individuais incluem estatísticas sobre o código de tipo e idade do usuário, o ano em que o usuário se registrou (somente desde 2003) e a intensidade com que o usuário tem utilizado o sistema de biblioteca (em termos de número de checkouts) desde o primeiro registro (Resumo extraído do Kaggle). 

Vocês poderão acessar os dados utilizados nesta análise [aqui](https://drive.google.com/file/d/1wTom0A8SRd7XlR-pBqu720O1rhOR41uD/view?usp=sharing).


### Questionamentos:
*    Quais são e qual a quantidade de usuários por tipo?
*    Quais são e qual a quantidade de usuários por faixa etária?
*    Quais são as bibliotecas e qual a quantidade de usuários  por bibliotecas?
*    Quantos empréstimos foram realizados? Por tipo de usuário e por biblioteca.
*    Quantas renovações foram realizadas? Por tipo de usuário e por biblioteca.
*    Quais são os tipos de recebimento de aviso? Qual a quantidade de usuários que preferem cada tipo? Quais são os tipos de usuários que preferem cada tipo?
*    Como está distribuída a frequencia de usuários que fornecem endereço de email? Quem são os usuários que não fornecem? 
*    Qual a quantidade de usuários que não são de São Francisco?
*    Qual a quantidade de usuários que não realizam empréstimos a mais de 1 ano?
*    Qual a distribuição da quantidade média de empréstimos realizados por ano por tipo de usuário?
*    Há uma correlação entre o número de empréstimos e de renovações?




## Considerações finais

A análise exploratória é uma fase importante e inicial em um projeto de ciência de dados. Com ela é possível entender melhor os dados para se responder alguns questionamentos e preparar eles para análises e questionamentos mais aprofundados.

Pude responder todos os questionamentos estabelecidos no início do projeto, entretanto a relação entre faixa etária e tipo de usuários ficou sem respostas, devido a sua falta de coerência.


Esta análise apenas deu o primeiro passo e fica aberto para outras pessoas estabelecerem novas perspectivas baseadas nesta.
