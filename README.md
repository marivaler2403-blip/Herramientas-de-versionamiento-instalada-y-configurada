FAMILIA@DESKTOP-IVQVDB7 UCRT64 ~
$ git --version
git version 2.56.0.windows.2

FAMILIA@DESKTOP-IVQVDB7 UCRT64 ~
$ git config --global user.name Jeisson Robayo

FAMILIA@DESKTOP-IVQVDB7 UCRT64 ~
$ git config __global user.email marivaler2403@gmail.com
fatal: not in a git directory

FAMILIA@DESKTOP-IVQVDB7 UCRT64 ~
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=schannel
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Jeisson

FAMILIA@DESKTOP-IVQVDB7 UCRT64 ~
$ git init
Initialized empty Git repository in C:/Users/FAMILIA/.git/

FAMILIA@DESKTOP-IVQVDB7 UCRT64 ~ (master)
$ git status
warning: could not open directory 'Configuración local/': Permission denied
warning: could not open directory 'Cookies/': Permission denied
warning: could not open directory 'Datos de programa/': Permission denied
warning: could not open directory 'Entorno de red/': Permission denied
warning: could not open directory 'Impresoras/': Permission denied
warning: could not open directory 'Menú Inicio/': Permission denied
warning: could not open directory 'Mis documentos/': Permission denied
warning: could not open directory 'Plantillas/': Permission denied
warning: could not open directory 'Reciente/': Permission denied
warning: could not open directory 'SendTo/': Permission denied
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .easyxmleditor/
        .gitconfig
        .lesshst
        .xmlhelper/
        3D Objects/
        AppData/
        Contacts/
        Desktop/
        Documents/
        Downloads/
        Favorites/
        Links/
        Music/
        NTUSER.DAT
        NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
        NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
        NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
        OneDrive/
        Pictures/
        Saved Games/
        Searches/
        Videos/
        ntuser.dat.LOG1
        ntuser.dat.LOG2
        ntuser.ini

nothing added to commit but untracked files present (use "git add" to track)

FAMILIA@DESKTOP-IVQVDB7 UCRT64 ~ (master)
$ git add README.md
fatal: pathspec 'README.md' did not match any files

FAMILIA@DESKTOP-IVQVDB7 UCRT64 ~ (master)
$ git status
warning: could not open directory 'Configuración local/': Permission denied
warning: could not open directory 'Cookies/': Permission denied
warning: could not open directory 'Datos de programa/': Permission denied
warning: could not open directory 'Entorno de red/': Permission denied
warning: could not open directory 'Impresoras/': Permission denied
warning: could not open directory 'Menú Inicio/': Permission denied
warning: could not open directory 'Mis documentos/': Permission denied
warning: could not open directory 'Plantillas/': Permission denied
warning: could not open directory 'Reciente/': Permission denied
warning: could not open directory 'SendTo/': Permission denied
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .easyxmleditor/
        .gitconfig
        .lesshst
        .xmlhelper/
        3D Objects/
        AppData/
        Contacts/
        Desktop/
        Documents/
        Downloads/
        Favorites/
        Links/
        Music/
        NTUSER.DAT
        NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
        NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
        NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
        OneDrive/
        Pictures/
        Saved Games/
        Searches/
        Videos/
        ntuser.dat.LOG1
        ntuser.dat.LOG2
        ntuser.ini

nothing added to commit but untracked files present (use "git add" to track)

FAMILIA@DESKTOP-IVQVDB7 UCRT64 ~ (master)
$ git commit -m Herramientas de versionamiento instalada y configurada
error: pathspec 'de' did not match any file(s) known to git
error: pathspec 'versionamiento' did not match any file(s) known to git
error: pathspec 'instalada' did not match any file(s) known to git
error: pathspec 'y' did not match any file(s) known to git
error: pathspec 'configurada' did not match any file(s) known to git

FAMILIA@DESKTOP-IVQVDB7 UCRT64 ~ (master)
$ git log -1 --oneline
fatal: your current branch 'master' does not have any commits yet

FAMILIA@DESKTOP-IVQVDB7 UCRT64 ~ (master)
$ git branch -M main

FAMILIA@DESKTOP-IVQVDB7 UCRT64 ~ (main)
$ git remote add origin https://github.com/marivaler2403-blip/SistemaClientesWeb.git

FAMILIA@DESKTOP-IVQVDB7 UCRT64 ~ (main)
$ git remote -v
origin  https://github.com/marivaler2403-blip/SistemaClientesWeb.git (fetch)
origin  https://github.com/marivaler2403-blip/SistemaClientesWeb.git (push)

FAMILIA@DESKTOP-IVQVDB7 UCRT64 ~ (main)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/marivaler2403-blip/SistemaClientesWeb.git'

FAMILIA@DESKTOP-IVQVDB7 UCRT64 ~ (main)
$ git status
warning: could not open directory 'Configuración local/': Permission denied
warning: could not open directory 'Cookies/': Permission denied
warning: could not open directory 'Datos de programa/': Permission denied
warning: could not open directory 'Entorno de red/': Permission denied
warning: could not open directory 'Impresoras/': Permission denied
warning: could not open directory 'Menú Inicio/': Permission denied
warning: could not open directory 'Mis documentos/': Permission denied
warning: could not open directory 'Plantillas/': Permission denied
warning: could not open directory 'Reciente/': Permission denied
warning: could not open directory 'SendTo/': Permission denied
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .easyxmleditor/
        .gitconfig
        .lesshst
        .xmlhelper/
        3D Objects/
        AppData/
        Contacts/
        Desktop/
        Documents/
        Downloads/
        Favorites/
        Links/
        Music/
        NTUSER.DAT
        NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
        NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
        NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
        OneDrive/
        Pictures/
        Saved Games/
        Searches/
        Videos/
        ntuser.dat.LOG1
        ntuser.dat.LOG2
        ntuser.ini

nothing added to commit but untracked files present (use "git add" to track)

FAMILIA@DESKTOP-IVQVDB7 UCRT64 ~ (main)
$ git log --oneline
fatal: your current branch 'main' does not have any commits yet

FAMILIA@DESKTOP-IVQVDB7 UCRT64 ~ (main)
$ ^C

FAMILIA@DESKTOP-IVQVDB7 UCRT64 ~ (main)
$
