## 1. Introdução

### 1.1. Objetivo

O objetivo deste documento é dissecar a arquitetura do projeto Kitchen Road, de modo que, todo a visão arquitetural do sistema que será desenvolvido esteja clara.
Outro ponto que será abordado, são as principais características do software permitindo que desenvolvedores/gestores entendam os processos que levaram na escolha das tecnologias e decisões a respeito dessa arquitetura.

### 1.2. Escopo

A Kitchent Road é uma PWA desenvolvida para pessoas de todas as idades que buscam aprender a arte da culinária. Sendo assim, a plataforma é uma página web, mas que tem como foco no uso em celulares.

Na plataforma o usuário cadastrado tem acesso a receitas e dicas de culinária, além disso, ele poderá acompanhar quantas receitas foram efetivadas e a cada receita feita o usuário receberá experiência.

### 1.3. Visão geral

Este documento é dividio nas seguintes seções:

- Introdução: Explica o propósito e organização do documento.
- Representação Arquitetural: Apresenta a arquitetura adotada para desenvolver o projeto.
- Metas e Requisitos de Software: Destrincha os requisistos de usabilidade do software, e as metas mais relevantes para o sistema que será desenvolvido.
- Visão de dados: Apresentação de todos os dados e métricas da aplicação.
- Visão de Casos de uso: Apresentação de todos os casos de uso da aplicação.
- Referências bibliográficas: Material de apoio na elaboração desse documento

### 1.4. Definições, acrônimos e abreviações

|**Sigla/Termo/Acrônimo**|**Definição**|
|--|--|
|API|Application Programming Interface|
|MVC|Model View Controller|
|REQ|Requisitos de Software|
|FGA|Faculdade do Gama|
|UNB|Universidade do Gama|
|DRF|Django REST Framework|
|ORM|Object-relational Mapping|

## 2.Representação de arquitetura

### 2.2. Tecnologias

|**Tecnologia**|**Descrição**|
|--|--|
|**Back-end**||
|Python|Linguagem para o desenvolvimento do backend|
|Django|Framework que segue a arquitetura MTV, fará comunicação do back com o banco de dados|
|Django REST Framework|Framework Django que permite a criação simples, ágil, poderosa e flexível de API's Web|
|||
|**Front-end**||
|JavaScript|Alia-se no desenvolvimento do frontend junto com HTML e CSS|
|React.js|Biblioteca em javascript com foco em criar inteface de usuário em páginas web.|
|HTML 5|Será utiliza para implementação do frontend junto ao JS e CSS|
|CSS|Linguagem para estilização de uma interface web|
|Bootstrap|Framework para desenvolvimento em HTML e JS.
|
|||
|**Banco de dados**||
|SQLite 3|Banco de dados relacional, será usado para gerir a base de dados|
|||

## 3. Metas e restrições da arquitetura

## 4. Visão de Dados

### 4.1. Modelo Entidade Relacionamento(MER)

#### Cozinheiro

| Atributos| Propriedade| Tipo| Descrição|
|--|--|--|--|
|idCozinheiro|Chave primária obrigatória|Integer|Identificador do cozinheiro|
|nome|Obrigatório|String|Nome do cozinheiro|
|email|Obrigatório|String|Email do cozinheiro|
|senha|Obrigatório|String|Senha de login|
|listaReceitasCompletadas|Optativo|Receita|Lista de receitas que o cozinheiro já efetuou|
|listaConquistaAdquiridas|Optativo|Conquista|Lista de conquistas que o cozinheiro adquiriu|

#### Receita

| Atributos | Propriedade | Tipo | Descrição |
|---|---|---|---|
| idReceita | Chave primária obrigatória | Integer | Identificador da receita |
| nome | Obrigatório | String | Nome da receita |
| modoPreparo | Obrigatório | String | passo a passo de como preparar a receita |
| dificuldade | Obrigatório | char | identifica a difícil da receita |
| listaCategoria | Obrigatório | Categoria | lista que identifica a categoria que pertence a receita |

#### Categoria

| Atributos | Propriedade | Tipo | Descrição |
|---|---|---|---|
| idCategoria | Chave primária obrigatória | Integer | Identificador da categoria |
| nome | Obrigatório | String | Nome da categoria |

#### Dicas


| Atributos | Propriedade | Tipo | Descrição |
|---|---|---|---|
| idDicas | Chave primária obrigatória | Integer | Identificador da dicas |
| titulo | Obrigatório | String | Título da dica |
| conteúdoDica | Obrigatório | String | Conteúdo escrito da dica |
| dificuldade | Obrigatório | char | Define o nível de dificuldade da dica |

#### Conquista
#### Administrador

|Atributos|Propriedade|Tipo|Descrição|
|--|--|--|--|
|idAdministrador|Chave primária obrigatória|Integer|Identificador do administrador|
|username|Obrigatório|String|Username do administrador|
|email|Optativo|String|Email do administrador|
|senha|Obrigatório|String|Senha de login|

## Visão de caso de uso

## Visão lógica

## Versionamento

|Data|Versão|Descrição|Autores|
|--|--|--|--|
|24|1.0|Criação do documento|Natanael Filho|