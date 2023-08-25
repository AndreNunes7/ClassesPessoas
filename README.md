# Sistema de Gestão de Pessoas

Este é um programa em C# que simula um sistema de gestão de pessoas, onde são representados alunos e professores com suas respectivas informações, como nome, data de nascimento, RG, CPF, sexo, entre outras. Os alunos podem ter telefones associados a eles, e o sistema permite exibir os detalhes de alunos e professores.

## Funcionamento

O programa define três classes principais:

- `Pessoa`: Classe abstrata que contém as propriedades e métodos básicos compartilhados por alunos e professores, como nome, data de nascimento, RG, CPF, sexo e telefones associados.

- `Aluno`: Classe que herda de `Pessoa` e adiciona propriedades específicas de alunos, como RA (Registro Acadêmico) e curso.

- `Professor`: Classe que herda de `Pessoa` e adiciona propriedades específicas de professores, como registro funcional e formação.

O programa também inclui um método `AddTel` na classe `Pessoa` para adicionar telefones à lista de telefones da pessoa e um método `listaTel` para exibir todos os telefones associados.

O método `Main` instancia alunos e um professor, atribui informações a eles e exibe os detalhes de cada um, incluindo telefones associados.

## Como usar

1. Certifique-se de ter o ambiente de desenvolvimento C# configurado em sua máquina.

2. Copie o código fornecido e cole-o em um arquivo `.cs`.

3. Compile e execute o programa.

4. O programa instanciará alunos e um professor, exibirá informações detalhadas sobre eles, incluindo telefones associados.

## Observações

- Este código é um exemplo didático para ilustrar o uso de classes, herança e propriedades em C# para modelar um sistema de gestão de pessoas. Ele pode ser estendido e aprimorado para incluir mais funcionalidades e casos de uso.

- É importante considerar a organização do código, a separação de responsabilidades e boas práticas de codificação ao desenvolver projetos mais complexos.

- O código poderia se beneficiar de comentários adicionais para explicar partes específicas do código e da lógica.

- Lembre-se de que esse código é um exemplo simplificado e não leva em consideração todas as complexidades do mundo real.
