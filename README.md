#latihan 1

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 /
$ pwd
/

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 /
$ cd ~

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~
$ cd lab_pemrograman/

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman
$ cd latihan1/
bash: cd: latihan1/: No such file or directory

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman
$ mkdir latihan1/

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman
$ cd latihan1/

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1
$ git init
Initialized empty Git repository in C:/Users/Bayu maulana ayassy/lab_pemrograman/latihan1/.git/

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ echo "#latihan 1" >> README.md

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ ls -l
total 1
-rw-r--r-- 1 Bayu maulana ayassy 197121 11 Oct 14 13:32 README.md

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git add README.md

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git commit -m "BAYU MAULANA AYASSY"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Bayu maulana ayassy@LAPTOP-OB2RGAL6.(none)')

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git config --global user.email "bayuwakwaww20@gmail.com
> git config --global.user "Bayu"
> git config --global user.name "Bayu"
> git config --global user.email "bayuwakwaww20@gmail.com
git config --global.user "Bayu"
git config --global user.name "Bayu"
error: unknown option `global.user'
usage: git config [<options>]

Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    --worktree            use per-worktree config file
    -f, --file <file>     use given config file
    --blob <blob-id>      read config from given blob object

Action
    --get                 get value: name [value-pattern]
    --get-all             get all values: key [value-pattern]
    --get-regexp          get values for regexp: name-regex [value-pattern]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [value-pattern]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-pattern]
    --unset-all           remove all matches: name [value-pattern]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    --fixed-value         use string equality when comparing values to 'value-pattern'
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    -t, --type <type>     value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --bool-or-str         value is --bool or string
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    -z, --null            terminate values with NUL byte
    --name-only           show variable names only
    --includes            respect include directives on lookup
    --show-origin         show origin of config (file, standard input, blob, command line)
    --show-scope          show scope of config (worktree, local, global, system, command)
    --default <value>     with --get, use default value when missing entry


Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git commit -m "bayu"
[master (root-commit) 428dbec] bayu
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git remote add origin https://github.com/Bayuayassy/tugas3.git

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git push -u origin master

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git status
On branch master
nothing to commit, working tree clean

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git push -u origin master
fatal: User canceled device code authentication
error: unable to read askpass response from 'C:/Program Files/Git/mingw64/bin/git-askpass.exe'
username for 'https://github.com': Bayuayassy
userremote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Bayuayassy/tugas3.git/'

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 254 bytes | 254.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Bayuayassy/tugas3.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git push -u origin masterser
error: src refspec masterser does not match any
error: failed to push some refs to 'https://github.com/Bayuayassy/tugas3.git'

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git push -u origin master
Everything up-to-date
branch 'master' set up to track 'origin/master'.

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git remote add origin https://github.com/Bayuayassy/tugas3.git
error: remote origin already exists.

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git clone https://github.com/Bayuayassy/tugas3.git
Cloning into 'tugas3'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

Bayu maulana ayassy@LAPTOP-OB2RGAL6 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ ls -l
total 1
-rw-r--r-- 1 Bayu maulana ayassy 197121 11 Oct 14 13:32 README.md
drwxr-xr-x 1 Bayu maulana ayassy 197121  0 Oct 14 14:10 tugas3/
![2022-10-14 (1)](https://user-images.githubusercontent.com/115678251/195797726-8b7a86fd-8210-4d63-b37d-53f2a5b72fea.png)
![2022-10-14 (2)](https://user-images.githubusercontent.com/115678251/195797740-5d48fec4-0e4a-4476-bfd4-e3850017249e.png)
![2022-10-14 (3)](https://user-images.githubusercontent.com/115678251/195797744-673d9272-4a5c-4b76-a160-eee3f0f3ca70.png)
![2022-10-14 (4)](https://user-images.githubusercontent.com/115678251/195797750-3b5d8b9b-539b-449d-af1e-6c2101f8c8c3.png)
![2022-10-14 (5)](https://user-images.githubusercontent.com/115678251/195797759-c1701a0e-2ca2-4e30-af75-b40f51b4c21c.png)
![2022-10-14](https://user-images.githubusercontent.com/115678251/195797766-40173a57-aaca-43e2-a87f-e527096f8d6a.png)
