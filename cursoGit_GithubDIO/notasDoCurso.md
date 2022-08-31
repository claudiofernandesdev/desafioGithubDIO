## Link para download do Git no Linux

[Link para download](https://git-scm.com/download/linux)



## Criando uma chave ssh no GitHub

[Link da Documentação](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)



## Comandos Git

### Comandos Básicos

1. ### git config
   
   Quando você está utilizando o Git pela primeira vez ou com uma instalação nova, em um projeto colaborativo, esse comando é fundamental para configurar sua identidade de usuário, inserindo informações como nome e email que serão empregadas em cada *commit*.
   
   Exemplo:
   
   **$ git config –global user.name “Seu nome”**
   
   **$ git config –global user.email “Seu email”**
   
   

2. ### git init
   
   Esse é o comando que você irá utilizar para criar um novo projeto de git. O comando irá criar um repositório novo em branco e, a partir daí, será possível armazenar seu código fonte, alterar, salvaguardar alterações etc.
   
   Exemplo:
   
   **$ git init**
   
   Se você já possui um repositório anterior ou deseja criar um repositório com um nome em específico, você pode passar o nome como parâmetro do comando:
   
   **$ git init <O nome do seu repositório>**
   
   

3. ### git status
   
   Este comando é utilizado para encontrar arquivos que tenham sofrido alterações em seu conteúdo, facilita a identificação dos arquivos que precisam ser substituídos no repositório que está em um servidor remoto
   
   Exemplo:
   
   **git status**
   
   

4. ### git add
   
   Quando se quer arquivos especificos.
   
   **git add nomeArquivo.extensão outroNomeArquivo.extensão**
   
   Quando todos os arquivos precisam ser adicionados, para não precisar digitar tantos nome, você pode substituir o nome dos arquivos por um * (asterisco)
   
   **git add** *
   

5. ### git commit
   
   Este comando permite adicionar uma mensagem junto ao arquivo, auxiliando na busca dos arquivos que foram alterados dentro do servidor remoto
   
   **git commit -m "Mensagem do commit"**
   
   

6. ### git clone
   
   Este comando pode ser utilizado para fazer download dos arquivos de um repositório local
   
   **git clone /caminho/para/o/repositorio**
   
   Este outro é utilizado para repositórios que estão em um servidor remoto
   
   **git clone usuário@servidor:/caminho/para/o/repositorio**
   
   

7. ### git push
   
   Este comando permite realizar o envio dos arquivos selecoinados anteriormente junto com a mensagem informada no commit, para dentro do servidor remoto (seu GitHub ou outra plataforma)
   
   **git push origin master**
   
   Se você não clonou um repositório existente e quer conectar seu repositório a um servidor remoto, você deve adicioná-lo com
   
   **git push add origin <servidor>**
   
   

        


