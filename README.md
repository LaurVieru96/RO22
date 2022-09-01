# RO22
RO22 group repository from SDA JavaScript




#### comenzi de git utile :

## git init 
pentru a intra in master/ main repository
## git clone  
( sau orice alt link de repository din gitlab, github, etc)
pentru a descarca pe calculatorul personal un proiect din github/gitlab/bitbucket sau orice alt repository online. 

## git status
verifica statusul unui repository

## git add -A      (sau git add . )
adauga toate fisierele noi (untracked files) in lista de modificari (changes)

## git commit -m "in ghilimele punem mesajul de commit"
pentru a impacheta toate modificarile noastre intr-un COMMIT. Orice modificare in proiect trebuie salvata si trimisa la server intr-un commit.

## git push
ca sa trimitem modificarile din commit-ul nostru catre server ( origin/main)

## git log --graph --oneline --decorate
va ofera informatii intr-o reprezentare grafica despre commit urile de pe un branch

## git fetch -all
pentru a aduce noile branch uri la tine pe calculator

## git branch -all
iti returneaza lista completa de branch uri disponibile in repository ul tau curent.

## git pull
iti ia ultimele modificari de pe branch ul pe care il urmaresti  ( tu ai main, iar pe server este origin/main)

## git reset --hard
reseteaza toate modificarile de pe branchul nostru local, fara modificarile deja intr-un commit

## git clean -f

sterge fisierele noi care nu sunt adaugate in modificari ( untracked)
## git config --global user.name "Your Name"
## git config --global user.email "youremail@yourdomain.com"
adauga user name si user email(cu care te-ai logat in gitlab) in .gitconfig ( aflat la C:/users/STUDENTUL/.gitconfig)



## git fetch 
aducem pe local toate branch urile noi

## git checkout -b <nume-branch>  
creem un branch nou <nume-branch> si ne si mutam pe el  

## git push -u origin <nume-branch-cum-vrem-sa-fie-pe-server-origin> 
dupa ce salvam modificarile de pe branch ul nostru in commit, putem crea un branch cu acelasi nume pe server (origin) ca sa fie public

## ## git merge <nume-branch>
ne aflam pe un branch, daca rulam aceasta comanda, ne va aduce modificarile de pe <nume-branch> pe branch ul nostru curent. 
nu poti da merge la un branch pe care te si afli. trebuie sa fii pe un alt branch decat <nume-branch>


## git push -d <remote_name> <branchname>
## git branch -D <branchname>
## push -d sterge branch ul de pe origin ( remote branch ) iar branch -D sterge branch ul local.

## git branch -a
afisaza toate branch-urile disponibile dintr un repository
