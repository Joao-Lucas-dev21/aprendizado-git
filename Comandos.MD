# Comandos mais usados

### Criar repósitorio:
~~~ 
git init
~~~

### Clonar um repositório existente:
~~~ 
git clone https://github.com/usuario/repositorio.git
~~~ 

### Ver o status atual do repositório:
~~~ 
git status
~~~ 

### Adicionar arquivos para commit
~~~ 
git add arquivo.txt  ~ #Adiciona um arquivo
git add . ~ #Adiciona todos os arquivos modificados
git add .txt ~ #Adiciona todos arquivos com a extensão txt
~~~ 

### Fazer commit das alterações:
~~~ 
git commit -m "Mensagem descritiva"
~~~ 

### Ver histórico de commits:
~~~ 
git log
~~~ 

### Criar e mudar de branch
~~~ 
git branch nova-branch ~ #Cria 
git checkout nova-branch ~ #Muda para a brach criada
git checkout -b nova-branch ~ #Faz tudo em só uma linha
~~~  

### Juntar uma brach à main
~~~ 
git checkout main
git merge nova-brach
~~~ 

### Enviar alterações para o gitHub
~~~ 
git push origin main
~~~ 

### Buscar e atualizar seu repositório local
~~~ 
git pull origin main
~~~ 
