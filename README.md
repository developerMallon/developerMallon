- 👋 Hi, I’m Full stach @developerMallon
- 👀 I’m interested in learn new technologies.
- 🌱 I’m currently learning Laravel to backend and VueJS to frontend

### Starting a Laravel project
- composer create-project laravel/laravel <PROJECT_NAME> --prefer-dist  
- cd PROJECT_NAME  
- php artisan serve  
- http://127.0.0.1:8000 <-This is a address the new project  

### Starting a VueJS project
- vue create <PROJECT_NAME>  
- cd <PROJECT_NAME>  
- npm run serve  
- http://127.0.0.1:8080 <-This is a address the new project  

## --------------- CREATE A NEW GIT REPOSITORY ---------------

```
https://mazer.dev/git-basico/

git init
git add .
git commit -m "first commit"
git branch -M master
git remote add origin git@github.com:developerMallon/mms.git
git push -u origin master -> Envia/sincroniza os dados com o repositório remoto (github)

git pull <- Verificar se tem alterações no repositório remoto
git merge <- Mescla as atualizações feitas no repositório com o local

git checkout -b <nome-da-branch> <- Cria e já muda para a nova branch

git checkout master -> Volta pra linha master
git merge <nome-da-branch> -> Mescla a branch com a master
git push -> aplica as atualizações na master  
  
--- REVERTER ARQUIVOS AINDA NÃO COMITADOS ---  
git checkout -- . -> reverte todas as alterações em arquivos que estavam versionados    
git clean -f -d   -> é para apagar todos os arquivos e diretórios criados  
  
--- REVERTER PARA UM COMMIT ESPECÍFICO ---  
git reflog  -> lisata todos os commits realizados  
git reset HEAD@{2} -> volta para o commmit ...{2}  
  
```
