# Features
<ul>
    <li>Novas funcionalidades</li>
    <li>develop -> feature</li>
    <li>develop <- feature</li>
    <li>git checkout develop</li>
    <li>git merge feature/registo</li>
</ul> 
<hr>


## Releases

<ul>
    <li>nova versão da aplicação</li>
    <li>develop -> release -> master</li>
    <li>git checkout develop</li>
    <li>git checkout -b release/1.0.0</li>
    <li>git checkout master</li>
    <li>git merge release/1.0.0</li>
</ul>

### Hotfix

<ul>
    <li>bugs</li>
    <li></li>
    <li>branch master e develop recebe a branch hotfix com as correções</li>
    <li>git checkout master</li>
    <li>git merge hotfix/recurso</li>
    <li>git checkout develop</li>
    <li>git merge hotfix/recurso</li>
    <li>git branch -D hotfix/recurso</li>
</ul>

####Para iniciar um projeto usando a extensão

git flow init

######Features 

develop -> feature

git flow feature start feature/register

git flow feature finish feature/register faz o merge no master e no develop

######Releases

git flow release start 1.0.0

git flow finish '1.0.0' faz o merge no master e no develop

######Hotfix

git flow hotfix start hotfix/recurso

git flow hotfix finish hotfix/recurso faz merge no master e no develop










