# Git Version Control

### ---------------- Principais comandos do git ------------------



## Configuração inicial 
```git config --global user.name <nome_usuario>```<br>
```git config --global user.email <email>```

Define o nome e o email do usuario globalmente.


## Iniciar um repositorio
```git init```<br>
Inicia um repositorio Git.


## Clonar um repositorio

```git clone <url-do-repositorio>```<br>
Clona um repositorio remoto.


## Trabalho com Branch
```git branch```  <br>
Retorna o resultado de qual branch o usuario esta dentro realizando modificações.

```git branch <nome da nova branch```  <br>
Cria uma nova branch para o projeto.

```git switch <nome da branch>```  <br>
Muda para uma outra branch ja existente.

```git checkout -b <nome da nova branch>```  <br>
Cria e muda para uma nova branch que foi criada.


## Adicionando alterações
```git add .``` <br>
Adiciona todas as alterações feitas no projeto ao proximo commit.

```git add <nome_do_arquivo>``` <br>
Adiciona um arquivo especifico ao proximo commit.


## Dando COMMIT
```git commit -m "Mensagem do commit"```<br>
Realiza o commit e manda menssagem para indicar as mudanças que foram feitas no projeto. <br>
**OBS:** É uma boa prática usar o commit semantico.

## Visualizar e comparar mudanças
```git status```<br>
 Mostra o estado das mudanças como não rastreadas, modificadas ou prontas para commit.

```git diff```<br>
 Mostra as diferenças entre os arquivos modificados e os commits.
 
## Integração de mudanças
 ```git merge <nome_da_branch>```<br>
 Mescla as mudanças de uma ramificação para a ramificação atual.

 ```git rebase <nome_da_branch>```<br>
Reorganiza os commits para ter uma linha de histórico mais limpa.

## Trabalhando com repositorio remoto
```git remote add origin <URL_do_repositorio>```<br>
Faz um link do repositorio local em que se esta trabalhando e o repositorio remoto.

```git push origin <nome_da_branch>```<br>
Manda as alterações/commits para o repositorio remoto.

```git pull <URL_do_repositorio>```<br>
Pega as alterações do repositorio remoto para atualizar o repositorio local.

## Historico de commit
```git log```<br>
Mostra o historico de commits, mostrando o autor e o hash, que é um identificador do commit.

## Desfazendo alterações
```git reset <hash_do_commit>``` <br>
Desfaz o commit especificado, mantendo as mudanças no working directory.

**OBS:** Pode também usar <nome_do_commit>.

**OBS2:** É necessário fazer um commit para lançar as alterações que foram desfeitas.


```git revert <hash_do_commit>``` <br>
Cria um novo commit que desfaz as mudanças do commit especificado.

**OBS:**  Ao contrário do git reset, o git revert não altera o histórico existente. Em vez disso, adiciona um novo commit que desfaz as alterações do commit alvo.


#### Outra forma é usar o HEAD, para que o git remova o ultimo commit que foi lançado.

 ```git revert HEAD``` <br>

Isso criará um novo commit, que desfaz as alterações introduzidas pelo commit anterior, a ser removido.

---

    Estes são os comandos mais utilizados com seus respectivos usos de uma forma mais basica e clara.