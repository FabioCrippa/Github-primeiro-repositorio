# Desafio de Projeto sobre Git/GitHub da DIO 
Repositório criado para o Desafio de Projeto

## Links úteis
[Sitaxe Básica Markdown] (https://www.markdownguide.org/basic-syntax/)

## Passo 1: criar respositório local
cadastrar o nome de usuário e e-mail para o git saber a identidade do projeto
No terminal:
//comando para cada projeto
>- git init //este comando cria um respositório local onde estão os arquivos
>- git config user.name "FabioCrippa"
>- git config user.name //este comando mostra se deu certo ou não
>- git config user.email "crippa.fabiocrippa@gmail.com"

//comando global para não ter de repetir os comandos anteriores em cada projeto
>- git --global user.name "FabioCrippa"
>- git --global user.email "crippa.fabiocrippa@gmail.com"

## Passo 2: conectar respositório local ao respositório remoto(nuvem)
No terminal:

git init 
git add "nomeDoArquivo" //este comando adiciona todas as modificações
git commit -m "primeiro commit" //este comando comita(salva) todas as modificações feitas. commit - pequenos pacotes armazenados no respositório. 
git branch -M main
git remote add origin https://github.com/FabioCrippa/aula-git1.git
git remote -v //este comando mostra se deu certo a conexão entre os respositórios
git push -u origin main //este comando envia todas as modificações ao respositório remoto

# Comandos git
## Comando para adicionar novas alterações ao arquivo
>-git add "nome do arquivo"
>-git commit -m "atualizando arquivo"
>-git push -u origin main

## Comando para adicionar vários arquivos ao mesmo tempo
>-git add .

## Comando para clonar arquivos do github
git clone - cria uma copia no computador de todos os arquivos remotos.
>-git clone https://github.com/FabioCrippa/Git.git

## Comando para baixar arquivos atualizados
git pull - baixa os arquivos que sofreram modificações atualizando o reposito que esta no computador 
>-git pull origin main
