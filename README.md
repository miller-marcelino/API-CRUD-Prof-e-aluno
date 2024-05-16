API de Cadastro Escolar
Este projeto consiste em uma API para cadastro de alunos e professores, oferecendo endpoints para realizar operações como cadastro, listagem, atualização e exclusão de registros.

Pacotes Utilizados
Spring Boot
Spring Data JPA
Hibernate Validator
Banco de Dados (configurado no arquivo application.properties)
Endpoints Disponíveis
Cadastro de Aluno
POST /CadastrarAluno: Endpoint para cadastrar um novo aluno. Aceita um JSON contendo os dados do aluno a ser cadastrado.
Cadastro de Professor
POST /CadastrarProfessor: Endpoint para cadastrar um novo professor. Aceita um JSON contendo os dados do professor a ser cadastrado.
Listagem de Alunos
GET /ListarAluno: Endpoint para listar todos os alunos cadastrados.
Listagem de Professores
POST /ListarProfessor: Endpoint para listar todos os professores cadastrados.
Exclusão de Aluno
DELETE /DeletarAluno/{matricula}: Endpoint para excluir um aluno com base em sua matrícula.
Exclusão de Professor
DELETE /DeletarProfessor/{matricula}: Endpoint para excluir um professor com base em sua matrícula.
Atualização de Aluno
PUT /AtualizaAluno/{matricula}: Endpoint para atualizar os dados de um aluno com base em sua matrícula. Aceita um JSON contendo os dados atualizados do aluno.
Atualização de Professor
PUT /AtualizaProfessor/{matricula}: Endpoint para atualizar os dados de um professor com base em sua matrícula. Aceita um JSON contendo os dados atualizados do professor.
Execução
Para executar o projeto localmente:

Clone este repositório em sua máquina local.
Certifique-se de ter o Java e o Maven instalados em sua máquina.
Configure o arquivo application.properties com as informações do seu banco de dados.
Execute o comando mvn spring-boot:run na raiz do projeto para iniciar o servidor.
Acesse os endpoints da API conforme documentado acima.
Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para propor melhorias, reportar problemas ou enviar pull requests.

Licença
Este projeto está licenciado sob a licença MIT - consulte o arquivo LICENSE.md para obter detalhes.