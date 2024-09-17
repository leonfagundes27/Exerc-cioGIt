# Exercício de Integração Contínua e Entrega Contínua

Este repositório foi criado como parte de um exercício da aula de Integração Contínua e Entrega Contínua, que consiste em uma série de passos utilizando Git e GitHub. Abaixo estão descritos os passos realizados e os comandos utilizados em cada etapa.

## 1. Configuração Inicial do Repositório

### A. Criação do Repositório
A. Acesse o GitHub e crie um novo repositório ou inicialize um repositório local.

B. Clonar o repositório:
    ```bash
   git clone https://github.com/usuario/nome-do-repositorio.git
    ```

C. Inicialize o repositório Git localmente:
    ```bash
    git init
    ```
D. Crie as branchs principais do GitFlow:
    - Master/Main
    - Development

    ```bash
    git checkout -b development
    ```
E. Faça o push das  branchs para o repositório remoto:

## 2. Configuração de uma Pipeline no GitHub Actions
A. Acesse a aba "Actions" no GitHub.

B. Clique em "New workflow" e selecione "Set up a workflow yourself".

C. Configure o arquivo YML de CI conforme as instruções do exercício.
