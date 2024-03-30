# Sistema de gerenciamento de escolas

#### Descrição e demandas do cliente

Quero um sistema de gerenciamento de escolas.

1 - Um login de admin, apenas admin poderá cadastrar escolas e ver a lista das escolas cadastradas.
Campos Login
CPF
Senha

2 - Cadastro de Escola
Campos de escola:
Id - Auto increment (gerado pelo sistema)
Nome Escola
Endereço escola.

3 - Um cadastro de professores que só o admin poderá cadastrar o professor.
Campos professor:
CPF
Nome
Escola -> listar as escolas cadastradas.

4 - Cada Professor cadastrado irá gerar um usuário de sistema com login e senha que o login será o CPF e a senha os 6 primeiros dígitos do CPF.

5 - O professor irá poder cadastrar um aluno com os seguintes campos.
Nome
Data Nascimento

6 - Um professor professor poderá listar os alunos e editar os alunos.

7 - Colocar o banco na raiz do projeto com os creates e dados necessário para rodar o projeto.

8 - Colocar o projeto no GitHub e adicionar nossos emails.




Login  por cpf e senha

Cadastro de usuário

Cadastro de escolas
Campos escola: Nome e endereço

Cadastro de professores -> Associando as escolas -> Cadas professor cadastrado irá gerar um usuário
Campos professor: Nome, cpf, senha, nascimento, escola

Cadastro de Alunos -> Associando a professores
Campos alunos: Nome, cpf, nascimento, professor


Plus:

Rodar o projeto com um comando no Docker. Se possível Docker compõe. Documentar todo o código