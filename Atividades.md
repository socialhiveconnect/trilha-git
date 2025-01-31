# **Atividades**

## **1. Introdução ao Versionamento de Código**
- **Leitura**: Pesquise e leia sobre o que é versionamento de código e por que ele é importante no desenvolvimento de software.
  - Sugestão: [O que é Git?](https://git-scm.com/book/pt-br/v2/Começando-O-que-é-Git%3F)
- **Tarefa**: Escreva um resumo explicando o conceito de versionamento de código.

---

## **2. Instalação e Configuração do Git**
- **Tarefa**: Instale o Git no seu computador.
  - Guia de instalação: [Instalando o Git](https://git-scm.com/book/pt-br/v2/Começando-Instalando-o-Git)
- **Tarefa**: Configure o Git com seu nome e e-mail.
  - Comandos:
    ```bash
    git config --global user.name "Seu Nome"
    git config --global user.email "seuemail@exemplo.com"
    ```
- **Validação**: Execute o comando `git config --list` para verificar se as configurações foram aplicadas corretamente.

---

## **3. Conceitos Básicos do Git**
- **Leitura**: Estude os principais conceitos do Git, como:
  - Repositório
  - Commit
  - Branch
  - Merge
  - Pull e Push
- **Tarefa**: Crie um arquivo Markdown com um glossário explicando cada um desses conceitos.

---

## **4. Criando e Gerenciando um Repositório Local**
- **Tarefa**: Crie um repositório local no seu computador.
  - Comandos:
    ```bash
    mkdir meu-repositorio
    cd meu-repositorio
    git init
    ```
- **Tarefa**: Crie um arquivo chamado `README.md` e adicione uma descrição do repositório.
- **Tarefa**: Faça o primeiro commit.
  - Comandos:
    ```bash
    git add README.md
    git commit -m "Primeiro commit: adicionando README.md"
    ```

---

## **5. Trabalhando com GitHub (ou GitLab/Bitbucket)**
- **Tarefa**: Crie uma conta no GitHub (ou GitLab/Bitbucket).
- **Tarefa**: Crie um repositório remoto na plataforma escolhida.
- **Tarefa**: Conecte o repositório local ao repositório remoto.
  - Comandos:
    ```bash
    git remote add origin https://github.com/seu-usuario/meu-repositorio.git
    git push -u origin main
    ```

---

## **6. Colaboração e Fluxo de Trabalho**
- **Leitura**: Estude sobre o fluxo de trabalho Git Flow e Pull Requests.
  - Sugestão: [Git Flow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)
- **Tarefa**: Convide um amigo para colaborar no seu repositório.
  - Crie uma branch chamada `feature/colaboracao` e peça para ele adicionar um arquivo.
  - Faça o merge da branch no `main`.

---

## **7. Resolvendo Conflitos**
- **Leitura**: Pesquise sobre como resolver conflitos no Git.
  - Sugestão: [Resolvendo Conflitos](https://git-scm.com/book/pt-br/v2/Git-Branching-Resolvendo-Conflitos)
- **Tarefa**: Simule um conflito de merge e resolva-o.
  - Crie duas branches (`feature1` e `feature2`) e edite o mesmo arquivo em ambas.
  - Faça o merge das branches no `main` e resolva o conflito.

---

## **8. Prática Contínua**
- **Tarefa**: Contribua para um projeto open-source no GitHub.
  - Encontre um repositório com a tag `good first issue` e envie um Pull Request.
- **Tarefa**: Crie um repositório pessoal para armazenar seus projetos e pratique o uso do Git diariamente.

---

## **Recursos Adicionais**
- [Documentação Oficial do Git](https://git-scm.com/doc)
- [Curso Gratuito de Git e GitHub](https://www.udemy.com/course/git-e-github-para-iniciantes/)
- [GitHub Learning Lab](https://lab.github.com/)

---