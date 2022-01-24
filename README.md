# Sistema integrado das bibliotecas de São Francisco: Uma análise exploratória dos dados

<p align="center"> 
<img src="https://cdn.vox-cdn.com/thumbor/ACMFacaANxBvqsRvN-Ps3WgG_Z8=/0x0:4221x2814/970x728/filters:focal(1774x1070:2448x1744):format(webp):no_upscale()/cdn.vox-cdn.com/uploads/chorus_image/image/62631916/14260954879_6846eafd66_o.0.jpg"></a> 
</p>

[Fonte](https://thewandererliteraryjournal.wordpress.com/2017/08/03/beautiful-public-california-libraries)


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
