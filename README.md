# Github Actions

**EM CONSTRUÇÃO...**

Plataforma de integração contínua e entrega contínua (CI/CD) que permite automatizar fluxos de trabalho de desenvolvimento de software diretamente em seu repositório.

# Workflows, Jobs and Steps

## Workflow

![Workflow](./img/github_workflow.png)

 - Anexado ao repositório GitHub;
 - Contém um ou mais jobs;
 - Iniciado por evento ou manualmente.

## Jobs

 - Define um Runner(ambiente de execução);
 - Contém um ou mais Steps;
 - Pode ser executado paralelamente ou sequencialmente;
 - Pode ter uma condição para ser executado. 

## Steps

  - Executa um shell script ou uma Action;
  - Pode ser customizado;
  - São executados em ordem;
  - Pode ter uma condição.


**Exemplo**

Repositório Git Hub:
  - Workflow 1
    - Job 1
        - Step 1
        - Step2
    - Job 2
        - Step 1
        - Step2

