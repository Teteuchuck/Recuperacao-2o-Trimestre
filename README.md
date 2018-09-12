# Desenvolvimento de Aplicações Web

**Data de Apresentação: 08/10/2018**

**Grupo: dois alunos**

**Valor: 13 pontos**

## Sistema Bibliotecário

A biblioteca do COLTEC decidiu atualizar o sistema de consulta às obras existentes em seu acervo, que atualmente está defasado. Para isso, a direção do colégio entrou em contato com o Setor de Informática no intuito de viabilizar a atualização do sistema.

Seu grupo deverá apresentar um primeiro protótipo do sistema, com as seguintes funcionalidades implementadas:

1. Cadastro de novas obras no acervo
1. Exibição das últimas obras cadastradas
1. Pesquisa às obras existentes

Você pode verificar em mais detalhes cada uma das funcionalidades abaixo:

### Cadastro de novas obras

O seu sistema deverá suportar o cadastro a novas obras. Para isso você deverá desenvolver uma interface que conterá um formulário de cadastro. Esse formulário deverá implementar mecanismo básicos de validação (tipo dos campos, formatação, etc.).

Ainda, para cada obra deverão se cadastrados os seguintes campos:

* Nome da obra
* Resumo da obra
* Nome do Autor
* Nome da Editora
* Nº de exemplares
* Data de cadastro da obra

### Exibição das últimas obras cadastradas

A página principal deverá listar as últimas obras cadastradas. A listagem poderá ser feita de duas formas: [grade](https://www.saraiva.com.br/universitarios/informatica) ou [lista](https://www.amazon.com.br/s?k=domain+driven+design&__mk_pt_BR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&ref=nb_sb_noss_2). Fica a critério do grupo definir como a listagem será feita.

Ainda, deverá haver uma barra de busca no topo da página, que será utilizada na funcionalidade a seguir.

### Pesquisa às obras existentes

A barra presente na página principal deverá permitir fazer a pesquisa das obras existentes na biblioteca. Essa pesquisa deverá abranger a busca pelo nome, autor ou editora. Os resultados da pesquisa deverão ser exibidos em uma nova página de listagem, que deverá mostrar a quantidade de registros pesquisados, seguidos da lista obtida a partir da busca.

## Apresentação

A apresentação do trabalho ocorrerá no dia **08/10/2018**, por meio de uma entrevista com os integrantes do grupo.

A apresentação será dividida em duas partes:

* **Explicação:** Apresentação sobre o sistema, principais funcionalidades, o que foi implementado, o que foi usado, etc. etc.
* **Demonstração:** Você irá executar o seu sistema e mostrar o funcionamento dos requisitos implementados.

**A apresentação irá avaliar o trabalho tanto do ponto de vista coletivo, como também individual!!** Portanto é de fundamental importância que o grupo mostre de forma clara quem foi responsável por desenvolver qual parte do projeto.

## Pilha de Tecnologias

Você estará livre para utilizar as bibliotecas e frameworks que considerar necessários. O uso de tais recursos inclusive é incentivado!!

Contudo, o desenvolvimento do trabalho **deve** englobar, de alguma forma, os seguintes conceitos:

* HTML
* CSS/SCSS
* JavaScript
* PHP: Classes, funções, etc.
* PHP: Sessões e Cookies
* PHP: Arquivos
* Banco de Dados

## Entrega

O trabalho deverá ser entregue no formato de pull-request. Além disso, o grupo deverá elaborar um pequeno documento (máximo 3 páginas), que ilustram o problema e sua motivação para resolvê-lo, a solução proposta, e as decisões técnicas tomadas na implementação do projeto.

Esse documento deverá ser entregue no dia da apresentação do trabalho.