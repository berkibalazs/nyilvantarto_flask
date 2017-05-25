

git beallitasa:
# git telepitese
,,,,,

apt install git
,,,

# git alap beallitasa
,,,,,
git config --global user.email "berkib007@gmail.com"
git config --global user.name "papevi"
,,,,,

#git push config:
,,,,

git config --global push.default matching
,,,,,

.gitignore filet tartalmazza azokat a mappakat vagy filokat amiket a git nem kell h figyelembe vegyen

# git hasznalata
1.csinalunk efy ures repositoryt, vagy clone-zunk egy meglevot...
uj ures repo keszitese:
git init

megleve klonozasa:
git clone /path/to/repo

eloszor hozzadajuk a commthoz azokat a filokat amiket fel szeretnenk push-olni:
pl a gitignore file-t

,,,,
  git add .gitignore
,,,,

pl ha az egesz mappat hozza akarjuk adni
