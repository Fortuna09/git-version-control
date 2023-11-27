# Git Version Control

## Principais comandos do git 



### Configuração inicial 
```git config --global user.name <nome_usuario>```<br>
```git config --global user.email <email>```<br>
Define o nome e o email do usuario globalmente.

---

### Iniciar um repositorio
```git init```<br>
Inicia um repositorio Git.


---
### Clonar um repositorio

```git clone <url-do-repositorio>```<br>
Clona um repositorio remoto.

---
### Trabalho com Branch
```git branch```  <br>
Retorna o resultado de qual branch o usuario esta dentro realizando modificações.

```git branch <nome da nova branch```  <br>
Cria uma nova branch para o projeto.

```git switch <nome da branch>```  <br>
Muda para uma outra branch ja existente.

```git checkout -b <nome da nova branch>```  <br>
Cria e muda para uma nova branch que foi criada.

---
### Adicionando alterações
```git add .``` <br>
Adiciona todas as alterações feitas no projeto ao proximo commit.

```git add <nome_do_arquivo>``` <br>
Adiciona um arquivo especifico ao proximo commit.

---

### Dando COMMIT
```git commit -m "Mensagem do commit"```<br>
Realiza o commit e manda menssagem para indicar as mudanças que foram feitas no projeto. <br>
**OBS:** É uma boa prática usar o commit semantico.























---

### 
