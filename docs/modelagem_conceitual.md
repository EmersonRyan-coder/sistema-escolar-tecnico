# Modelagem Conceitual

Explicação do sistema escolar baseado na visão do aluno.

Criei esse diagrama utilizando draw.io.

[Diagrama](../diagrama_v1.jpeg)

Esse diagrama representa a estrutura de um sistema de escola técnica, focado na visão do aluno. Partes como administrativas e outras foram abstraídas.

O foco desse diagrama é para entender como que as entidades se relacionam dentro do sistema.


#📌observações:
- As PKs estão destacadas em verde.
- As FKs estão destacadas em roxo.
- Nessa explicação o foco é sobre os atributos e relacionamentos.
- A explicação das entidades começa a partir do segundo atributo, sem detalhar a chave primária.

# Explicação das entidades

## Aluno
Representa o estudante no sitema.
Atributos:
- Nome
- CPF
- Data de nascimento
- Telefone
- Email
- Endereco

 ## Matrículas
Relaciona o aluno com a turma.
Cada atributo indica:
- FK ID aluno: identificador do aluno
- FK ID turma: identificador da turma
- Data matricula: Data que foi criada a matrícula
- Status: indica se a matricula está Ativa, Trancada, Em espera ou Cancelada.

## 🚨 Em desenvolvimento
A documentação ainda não está completa.
As explicações e alterações serão adicionadas progressivamente.
