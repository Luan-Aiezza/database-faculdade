# database-faculdade
Um simples banco de dados para administrar os dados dos alunos de uma faculdade.

A simple database to manage college student data.

# Regras de negocio (trading rules)
- Português
  
Um aluno só pode estar matriculado em um curso por vez;

Alunos possuem um código de indentificação (RA);

Cursos são compostos por disciplinas;

Cada disciplina terá no máximo 30 alunos por turma;

As disciplinas podem ser obrigatórias ou optativas, dependendo do curso;

As disciplinas pertencem a departamentos;

Cada disciplina possui um código de indentificação;

Alunos podem trancar matrícula, não estando então em nenhuma disciplina;

Em cada semestre, cada aluno pode estar matriculado em no máximo 9 disciplinas;

O aluno só pode ser reprovado no máximo 3 vezes em uma disciplina;

A faculdade terá no máximo 3000 alunos matriculados simultaneamente, em 10 cursos distintos;

Entram 300 alunos novos por ano;

Existem 90 disciplinas no total;

Um Histórico Escolar traz todas as informações da disciplina cursada por um aluno;

Professores podem ser cadastrados mesmo sem lecionar disciplinas;

Existem 40 professores trabalhando na faculdade;

Cada professor lecionará no máximo 4 disciplinas;

Cada professor é vinculado a um departamento;

Professores tem um código de professor;
