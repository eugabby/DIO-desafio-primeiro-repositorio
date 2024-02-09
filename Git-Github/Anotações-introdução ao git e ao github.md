# **Introdução ao Git e ao Github** 

- **Comandos básicos para um bom desempenho no terminal (CMV)** 

Listar = dir 

Navegar entre as pastas = cd/ 

Voltar = cd .. 

Entrar na pasta = cd + nome da pasta 

Limpar a tela = CTRL + l 

TAB = função autocompletar 

Criar pasta = mkdir + nome da pasta 

Deletar pasta = rmdir + nome da pasta /s /q 

Criar arquivo = echo hello > hello.txt 

Deletar arquivo = del + nome da pasta 

 

**Entendendo como o Git funciona por baixo dos panos** 

- **SHA 1** 

A sigla SHA significa Secure Hash Algorithm (Algoritmo de Hash Seguro), é um conjunto de funções Hash criptográficas projetadas pela NSA (Agência de Segurança Nacional dos EUA). 

A encriptação gera conjunto de 40 caracteres identificador de 40 dígitos. 

- **Chaves SSH e Tokens** 

**Primeiros comandos com o Git** 

- **Iniciar o Git** 

**Criando um repositório:** 

- Ls 
- Cd workspace/ 
- Mkdir livro-receitas 
- Ls 
- Cd livro-receitas/ 
- Git init 
- Ls 
- Ls –a (mostra pasta oculta) 
- Cd .git/ 
- git config --global user.email "Digite seu e-mail" 
- git config --global user.name "Digite seu usuário" 

**Adicionando um arquivo:** 

- Abrir um editor de texto e renomear: nome.md (typora) 
- Adicionar o texto no editor 
- Git add * 
- git commit -m "commit inicial" 

 

**Ciclo de vida dos arquivos** 

- Git status 
- mv strogonoff.md.txt ./receitas/ 
- git status 
- git add strogonoff.md.txt receitas/ 
- git commit -m "cria pasta receitas, move arquivo para receitas" 
- echo > README.md 
- git add * 
- git commit -m "adiciona index" 

**Trabalhando com o Git Hub** 

- git config –list 
- git remote add origin https://github.com/eugabby/livro-receitas.git 
- git remote -v 
- git branch -m main 
- git push -u origin main 

 

**Resolvendo conflitos no Github** 

- git pull origin main (puxar as modificações feitas no Github) 
