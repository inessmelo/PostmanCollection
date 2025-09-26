# 📌 Postman Collection

 - [ServeRest](https://serverest.dev/#/): é uma API REST gratuita que simula uma loja virtual com intuito de servir de material de estudos de testes de API.
 - [FakeRESTApi.Web V1](https://fakerestapi.azurewebsites.net/index.html): é uma API REST gratuita que simula o cadastro de Livros e Autores para servir de material de estudos de testes de API.

## 🎯 Propósito do Repositório

Este repositório tem como único objetivo servir de espaço para estudos e testes pessoais, com foco no aprendizado e prática de testes de serviços (APIs).

> ⚠️ Importante:
> - O conteúdo aqui presente não deve ser utilizado em ambientes produtivos.   
> - O repositório não representa um produto final, mas sim um ambiente experimental para treinamento, aprimoramento de habilidades e validação de conceitos relacionados a testes de API.   
> - As implementações podem sofrer alterações constantes durante o processo de aprendizagem.   

## 📖 Índice

>Sobre o Projeto
Tecnologias Utilizadas
Estrutura do Projeto
Como Executar
Resultados e Demonstrações
Aprendizados e Contribuições
Próximos Passos 

## 📝 Sobre o Projeto

- Objetivo principal: Servir como ambiente de estudo contínuo e aperfeiçoamento em testes de serviços (APIs).  
- Contexto: Projeto criado no âmbito de desafios de QA e prática pessoal, com foco no desenvolvimento de habilidades em automação de testes.   
- Problemas abordados:   
  - Implementação de automação de testes para permitir a reutilização de dados criados em diferentes requisições.   
  - Automação da geração de massa de dados, reduzindo retrabalho manual.    
  - Uso de randomização de dados dentro das coleções do Postman, garantindo maior robustez e variedade nos cenários de teste.

## 🛠 Tecnologias Utilizadas

- Principais ferramentas, linguagens e tipo de teste utilizadas nessa collection:
- Linguagem: JavaScript
- Ferramentas: Postman, GitLab , Newman, JS
- Tipos de Teste: Teste Funcional, Teste de Performance e Automação

## 📂 Estrutura do Projeto

- Postman Collections = Collection do Postman de cada API Rest  
- README.md = Arquivo de informação sobre o projeto de teste
- ServeRest = API de cadastro de Usuários, Produtos e inserir produtos no carrinho
- Fake Rest API = API ded cadastro de Livros e Usuários

## ▶️ Como Executar

- Geração de token SSH no GitHub para permitir a automação dos envios dos testes, eliminando a necessidade de executar manualmente comandos Git (opcional).
- Criação de relatórios detalhados (Status Report) utilizando o Newman via linha de comando, garantindo maior visibilidade e rastreabilidade dos resultados dos testes.
- Rodar o Newman   ` newman run -h ` e o Report HTML `-r htmlreport`


## 📊 Resultados e Demonstrações

- Instalando o [Node.JS](https://nodejs.org/pt)) e o NPM vem junto com a instalação Node; 
- Verifciar via linha de comando no GIT Bash se o Node e o NPMM foram isntalados com `node -v` e `npm -v` ;
- Instalar o Newman com `npm install -g newman` via linha de comando; 
- Instalar o Report Newman em HTML com `npm install -g newman-reporter-htmlextra` via linha de comando; 
- Exportar toda a Collection e toda a Environment e add em um pasta;
- Rodar o GIT Bash dentro dessa pasta com a seguinte linha de comando `run newman NomeDaCollection.postman_collection.json -e NomeDaEnvironment.postman_environment.json -r htmlextra
` ;
  
<img width="1049" height="805" alt="image" src="https://github.com/user-attachments/assets/eccf8acd-9717-4d5d-a3fb-e0caa2d95dc7" />



## 🚀 Aprendizados e Contribuições

- Criação de scripts em JavaScript para geração de massa de dados utilizada nas requisições.   
- Reaproveitamento da massa de dados gerada em requisições anteriores para utilização em chamadas subsequentes.   
- Expansão e detalhamento de cenários de teste dentro de cada requisição, cobrindo suas respectivas rotas.   
- Geração de relatórios de execução (Status Report) por meio da integração do Newman com o Postman.
- Automatizar a subida dos testes do Postman em tempo real para o GitHub sem efetuar comando GIT.   


## 📌 Próximos Passos

> - Adicionar testes de regressão
> - Criar relatórios automáticos de QA
> - Expandir documentação

## 👩‍💻 Autor(a)

Ines Melo   /   <a href="https://www.linkedin.com/in/in%C3%AAs-m-065b8681/">LinkedIn</a>   /   <a href="https://gitlab.com/inessmelo/postmancollection/-/tree/main">GitLab</a>
