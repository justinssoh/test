Test Repo
==================================================
**Table of Contents**
* [ 0. Prerequisite ]( # prerequisite )
    - Github Accout
    - git
    - Set up Git
* [ 1. Online Repository ]( #online-repository )
* [ 2. Local Repository ]( #local-repository )
* [ 3. Connect Local Repository to GitHub Repository ]( #connect )

<br>


Prerequisite
==============================
    * Guthub Account
    * git

## Set up Git
```
git config --global user.name "justinssoh"
git config --global user.email "justinssoh@gmail.com"

# ~/.gitconfig
```

<br>
Online Repository
==============================
## New test Repo on github.com
```
# Logon

https://github/new

# After create new Repo
    * README.md
    * LICENSE
    * .gitignore
```
https://github.com/justinssoh/test

<br>


Local Repository
==============================
## Local Directory
    * Overview
/media/justin/TOSHIBA EXT/jWORK/GIT
```
.
└── test
    └── README.md       # This REAME.md
```

    * init
```
mkdir test
cd test

git init
git status
```

    * add
```
git add README.md

```

    * commit
    ```
    git commit -m "Add README.md"
    ```

<br>


Connect Local Repository to GitHub Repository
==================================================
# 원격 저장소의 이름(별명)을 각각 origin , memo 지정한다.
❯ git remote add origin https://github.com/wayhome25/gitfth.git
❯ git remote add memo https://github.com/wayhome25/memo.git
❯ git remote
memo
origin
```
git remote add origin https://github.com/justinssoh/test

git remote -v

# 로컬저장소를 origin 원격저장소의 master 브랜치로 연결하여 push한다
# 처음에 한번만 -u 설정을 하면 앞으로 git push 만 입력해도 origin의 master 브랜치로 push한다
git push -u origin master
```

