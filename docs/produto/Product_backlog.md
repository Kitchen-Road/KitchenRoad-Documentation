# Product Backlog

## Ferramenta:

<p align = "justify">&emsp;&emsp; Para o gerenciamento de requisitos vamos utilizar o Jira, que é uma plataforma que oferece suporte ao desenvolvimento ágil e roadmap de produtos, para diversos tipos de projetos, inclusive para equipes de software. O Jira oferece suporte para gerenciar seus problemas do GitHub, quadros com vários repositórios, Epics e relatórios.</p>

## Tema de Investimento:

O tema de investimento foi definido como **Gamificação da culinária**.

## Épicos

| ID | DESCRIÇÃO |
|---|---|
| EP01 | Autenticação e Conta |
| EP02 | Gerência de Receitas. |
| EP03 | Gamificação. |
| EP04 | Comunidade. |

## Funcionalidades (Features)

| Épico | FEATURE | DESCRIÇÃO |
|---|---|---|
| E1 | FT1 | Cadastro e login de usuário. |
| E2 | FT2 | Definição de receitas. |
| E2 | FT3 | Listagem de receitas. |
| E2 | FT4 | Interagir com receitas. |
| E2 | FT5 | Feedback de usuários |
| E3 | FT6 | Conquistas. |
| E3 | FT7 | Timer de preparo. |
| E4 | FT8 | Implementações da comunidade. |

## 3. User Stories

| Épico | Feature | US | Descrição | Critérios de aceitação | Pontuação |
|---|---|---|---|---|---|
| E1 | FT1 | US01 | Eu como usuário gostaria de me cadastrar na plataforma para que possa utilizar o sistema. | - Os usuários devem conseguir acesso à plataforma após o cadastro. | 8 |
| E1 | FT1 | US02 | Eu como usuário gostaria de logar no sistema por meio de redes sociais ou pelo cadastro da própria plataforma para que possa acessar o sistema. | - O usuário deve conseguir acessar as funcionalidades do sistema após realizar o login. | 8 |
| E1 | FT1 | US03 | Eu como usuário gostaria de recuperar minha senha para que eu possa readquirir acesso ao sistema. | - Os usuários devem conseguir recuperar ou restaurar a senha a qualquer momento, e ter acesso a plataforma com o novo texto-chave. | 13 |
| E1 | FT1 | US04 | Eu como cozinheiro gostaria de fazer um quiz para que eu possa saber em que nível de conhecimento estou. | - O quiz deve garantir no final qual é  nível de experiência do cozinheiro(Iniciante/Intermediário/Experiente). - O usuário só terá acesso a esse quiz quando for cadastrar na plataforma. | 5 |
| E2 | FT2 | US05 | Eu como administrador, quero registrar receitas, para que os usuários possam visualizá-las. | - A receita deve conter os ingredientes e modo de preparo. - Os usuários devem ser capazes de visualizá-las. | 8 |
| E2 | FT2 | US06 | Eu como administrador quero excluir receitas, para que receitas incorretas possam ser retiradas. | - Os usuários não devem poder visualizar as receitas excluídas. - Deve ser apresentado um diálogo de confirmação para o administrador ao tentar excluir . | 8 |
| E2 | FT2 | US07 | Eu como administrador quero registrar categorias de receitas, para que os cozinheiros possam filtrá-las. | - Os usuários devem ser capazes de visualizá-las. | 10 |
| E2 | FT2 | US08 | Eu como administrador quero apagar categorias, para não poluir o sistema com categorias não utilizadas. | - Os usuários não devem poder visualizar as categorias excluídas. - Deve ser apresentado um diálogo de confirmação para o administrador ao tentar excluir . | 10 |
| E2 | FT2 | US09 | Eu como cozinheiro gostaria de postar receitas, para que eu possa contribuir com a comunidade. | - Essas receitas precisarão passar por uma filtragem feita por um nutricionista para serem aceitas na comunidade. - As receitas deverão seguir o mesmo modelo das receitas do sistema(Área de ingredientes e modo de preparo). | 20 |
| E2 | FT3 | US10 | Eu como cozinheiro quero que as receitas sejam separadas por dificuldade, para que eu execute as receitas do meu nível. | - O sistema deve exibir o nível de dificuldade de cada receita. - A cada certo número de receitas concluídas o usuário poderá acessar outros níveis de dificuldade. | 6 |
| E2 | FT3 | US11 | Eu como cozinheiro quero pesquisar um ingrediente para que eu encontre receitas com algo específico. | - Um campo de pesquisa deve ser criado. - O usuário deve conseguir acessar as receitas disponíveis apenas para o seu nível. | 10 |
| E2 | FT3 | US12 | Eu como cozinheiro quero que minhas restrições alimentares sejam respeitadas, para que minha saúde seja preservada. | - Os usuários poderão sugerir receitas que se adequem às suas restrições. - Essas receitas precisarão passar por uma filtragem feita por um nutricionista. | 8 |
| E2 | FT3 | US13 | Eu como cozinheiro gostaria de ver as receitas que fiz, para que eu saiba o quanto eu evoluí. | - O usuário deve acessar seu histórico de receitas feitas. | 5 |
| E2 | FT4 | US14 | Eu como cozinheiro quero favoritar receitas, para que consiga separar minhas receitas favoritas das gerais. | - O usuário deve ter acesso às receitas favoritas em uma sessão separada. - Uma opção de favoritar deve estar presente na página da receita | 24 |
| E2 | FT4 | US15 | Eu como cozinheiro gostaria de dar um feedback às receitas para que outros usuários possam ver. | - O usuário deve conseguir avaliar as receitas. - Os usuários devem conseguir visualizar as avaliações das receitas. | 13 |
| E2 | FT5 | US16 | Eu como administrador quero ver o feedback cedido pelos usuários, para que possa melhorar o sistema. | - Os feedbacks devem estar organizados numa sessão própria aos administradores. | 6 |
| E2 | FT5 | US17 | Eu como cozinheiro gostaria de receber sugestões que eu possa  melhorar meus conhecimentos. | - Deve haver sugestões relacionadas a receita | 10 |
| E2 | FT5 | US18 | Eu como cozinheiro gostaria de denunciar a postagem de outro usuário, para que o conteúdo ofensivo seja moderado. | - Ao acessar a postagem, o usuário deve conseguir denunciar aquele post. | 13 |
| E3 | FT6 | US19 | Eu como desenvolvedor gostaria de criar conquistas para o usuário, de modo que ele tenha um troféu que mostra a evolução do caminho dele. | - As conquistas serão obtidas e visualizadas pelo usuário após ele ter cumprido o desafio proposto. | 13 |
| E3 | FT6 | US20 | Eu como administrador gostaria de realizar um sistema de ranking de usuários para que eles possam se empenhar mais. | - O ranking deve ser atualizado instantaneamente. - Os 10 melhores receberão um prêmio, podendo ser conquistas, moedas e até descontos em lojas. | 20 |
| E3 | FT6 | US21 | Eu como cozinheiro quero concluir receitas para que eu possa avançar de nível na plataforma. | - O usuário deve conseguir marcar a receita como feita. - Ao realizar uma receita, a experiência do usuário deve aumentar. | 5 |
| E3 | FT6 | US22 | Eu como cozinheiro gostaria de ver minhas conquistas para que eu possa acompanhar meu progresso. | - O usuário deve acessar seu histórico de conquistas. | 10 |
| E3 | FT7 | US23 | Eu como cozinheiro quero que a plataforma tenha um cronômetro para não errar o tempo de cada etapa da receita. | - A plataforma deve ter um cronômetro disponível para o usuário. - O usuário deve conseguir iniciar, pausar e interromper a contagem do cronômetro. | 6 |