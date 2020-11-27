
## Komandas

`git init`


`git add FAILA_NOSAUKUMS`

`git status`

Tas mums deva informāciju par izveidotajiem failiem.

Pievienojām REMOTE tikai pirmajā reizē.

`git remote add origin git@github.com:vecbralis/git-liepu-2020.git`

Izveidojam komentāru

`git commit -m 'KOMENTARS'`

Un push uz MASTER

`git push origin master`

Vissdrīzākais izmeta kļūdu, ka vajag pull.

`git pull origin master`

un tad vēlreiz mēģinam

`git push origin master`

Ja nestrādā pull tad izmanotojam pirmajā reizē.

`git pull origin master --allow-unrelated-histories`

Lai izveidotu jaunu branch

`git checkout -b martins`
