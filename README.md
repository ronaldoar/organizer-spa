# organizer-spa
sistema de controle de atividades

====================================================================================================================
	PROJETO: ORGANIZER - DOCUMENTO DE ESPECIFICAÇÕES TÉCNICAS
	Obs: metodologia Scrum será aplicada aqui.
====================================================================================================================

Necessidade:
------------
Desenvolver um sistema web que possa ser utilizado através dos navegadores:
Chrome, Edge e Mozila.


Proposta:
---------
Desenvolver o back-end do sistema na plataforma Java utilizando o framework Spring Boot version 2.4.1.
Desenvolver o front-end do sistema em html, javascript e css utilizando os frameworks Angular version 9.1.11  e Bootstrap 3.1


Organização para o desenvolvimento:
----------------------------------
Back-end: todos devem participar;
Front-end: quem quiser participar.

OBS:
As histórias de usuário no contexto técnico serão todas escritas neste documento.
O repositório do projeto será o Git e GitHub.
APIs podem ser adicionadas ao projeto.


====================================================================================================================
	PROJETO: ORGANIZER - DOCUMENTO DE NEGÓCIO.
	Obs: metodologia Scrum será aplicada aqui.
====================================================================================================================

Necessidade:
------------
Em diversas ativadades que uma pessoa possui em seu dia-a-dia, muitas delas podem ser registradas, analisadas
e acompanhadas no decorrer de um determinado período de tempo. Um sistema de computador pode em muito facilitar
esse trabalho.
Pessos possuem necessidades básicas de cadastrar seus contatos, contas para pagar, valores de serviços para receber,
seus próprios dados pessoais, precisam fazer planejamentos semanais, mensais, anuais, precisam de uma agenda de
compromissos, precisam relacionar um determinado contato com um determinado compromisso, ou um contato com uma
pendência financeira etc.
As pessos precisam de relatórios para acompanhar o progresso de suas atividades.


Proposta:
---------
Em resumo, a ideia do projeto é registrar e organizar atividades de uma pessoa.
O sistema precisa ser dividios em módulos, o escopo do negócio será aberto, ou seja
muitas mudanças podem ser efetuadas até que seu objetivo básico seja concluído.
Os primeiros módulos necessários a concepção do projeto são:

Perfil do Usuário;
Compromissos/Contatos;
Controle Documentos;
Controle Financeiro;
Planejamentos;







------------------------------------------------------------------------------------------------------------------
	USER HISTORIES:
------------------------------------------------------------------------------------------------------------------
001-HU:
Criação do projeto no Spring Boot.

002-HU:
Criação do projeto no Angular.

003-HU:
Disponibilizar o projeto no GitHub e adicionar os desenvolvedores.

004-HU:
Perfil básico do usuario.
Cadastrar os dados mais básicos do usuario para que possa acessar o sistema.
Dados: nome, sobrenome, email, celular, telefone, login e senha.

005-HU:
Cadastrar os contatos do usuário:
Dados: matricula, nome, sobrenome, apelido, email, celular, telefone, chave-pix.

006-HU:
Consultar contatos do usuário:
Atributos de consulta: nome, sobrenome, email, apelido.

007-HU:
Alterar dados do contato.

008-HU:
Gerar relatorio do contato.
Formatos: pdf, xlsx

008-HU:
Cadastrar a entidade Documento.



