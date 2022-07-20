## <b> Comandos básicos: (windows)</b>
<br>

<b> Dir = </b> traz uma lista de diretórios contidas na pasta a qual estou situada  

<b> Cd / = </b> permiti que a gente navegue entre as pastas 

<b> Cd .. = </b> volta uma navegação / sai da pasta 

<b> Ctrl + l = </b> limpa a tela    

<b> TAB = </b> quando usamos a tecla TAB ele completa o nome da pasta que está dentro do windows 

 
<b> Mkdir = </b> para criar pastas exemplo: mkdir workspace 

 
<b> Echo = </b> Para criar um arquivo = exemplo: 

 Echo hello > hello.txt 
<br>

Nos dois exemplos acima foi criado uma pasta chamada workspace e um arquivo dentro dessa pasta chamado hello.txt 
<br>

<b> Del = </b> caso eu queira excluir tudo que estiver dentro de tal pasta, exemplo:  

Del workspace, ira deletar todos arquivos dentro da pasta workspace 

 
<br>
<b> Rmdir = </b> para deletar/remover repositório e tudo que estiver dentro, exemplo: 

Rmdir workspace /S  / Q 
<br>
<br>
 

## <b> Chave SSH: </b> 

O que é? 

-> de forma resumida, é uma forma de estabelecer uma conexão segura e encriptada entre duas maquinas 
 <br>
 <br>

## <b> Iniciando o Git e criando um commit: </b>

<b> Git init = </b> para iniciar o repositório no Git 

<b> Git add = </b> mover arquivos e dar início ao versionamento 

<b> Git commit = </b> para criar o commit 
<br>
<br>
 

## <b> Algumas configurações iniciais: </b>

1 -  git config  --global  user.email "rebeca_nasciment@outlook.com" 

2  - git config  –global user.name Rebeca 
<br>

<b> Git push = </b> envia o arquivo do repositório local para o remoto 

<b> Git Pull = </b> é usado para buscar e baixar conteúdo de repositórios remotos e fazer a atualização imediata
 ao repositório local para que os conteúdos sejam iguais. 
<br>
<br>

## <b> Envio de arquivos para o Github: </b>

 
1 - Primeiro criar um novo repositório no git hub 

2 - depois pegar a url/caminho

3 - ir no terminal ou git bash 

4 - já dentro da pasta que vou subir para o github, digitar 

git remote add origin e a url que vai ter sido gerada anteriormente 
<br>
<br>

(quando fizer alteração de algum arquivo ou codigo, é necessario fazer o commit)
<br>
<br>

## <b> Resolvendo conflitos no Git e GitHub: </b>
 <br>
Os conflitos acontecem quando as alterações nos arquivos não batem  

git push origin master  

Para clonar um repositório é necessário entrar no github, copiar a url, e colar juntamente com o comando ˋˋˋgit clone´´´