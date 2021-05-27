Last login: Thu May 27 12:50:45 on ttys000

~ via 🐘 v7.3.24
➜ cd code/cs101

~/code/cs101 via 🐍 3.7.7
➜ code .

~/code/cs101 via 🐍 3.7.7
➜ pwd
/Users/robinzuschke/code/cs101

~/code/cs101 via 🐍 3.7.7
➜ ls
my_first_script.py

~/code/cs101 via 🐍 3.7.7
➜ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint: 	git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint: 	git branch -m <name>
Initialized empty Git repository in /Users/robinzuschke/code/cs101/.git/

cs101 on  master [?] via 🐍 3.7.7
➜ git commit -m 'My first commit'
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	my_first_script.py

nothing added to commit but untracked files present (use "git add" to track)

cs101 on  master [?] via 🐍 3.7.7
➜ git remote add origin git@github.com:Robstaa/python_hello_world.git

cs101 on  master [?] via 🐍 3.7.7
➜ git add .

cs101 on  master [+] via 🐍 3.7.7
➜ git commit -m 'My first commit'
[master (root-commit) 8837559] My first commit
 1 file changed, 3 insertions(+)
 create mode 100644 my_first_script.py

cs101 on  master via 🐍 3.7.7
➜ git push origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 293 bytes | 146.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:Robstaa/python_hello_world.git
 * [new branch]      master -> master

cs101 on  master via 🐍 3.7.7 took 5s
➜ https://github.com/Robstaa/python_hello_world
zsh: no such file or directory: https://github.com/Robstaa/python_hello_world

cs101 on  master via 🐍 3.7.7
➜ git clone git@github.com:Robstaa/python_hello_world.git

cs101 on  master via 🐍 3.7.7
➜ cd ..

~/code
➜ ls
Alfred.Workflow.Todoist.alfredworkflow chrome-plugin-esade                    graph                                  ml                                     test-css
GamestonkTerminal                      cs101                                  hello                                  phaser                                 tindex_Lunar
Untitled Folder                        django                                 jordi                                  plurapolit                             tryhackme
Untitled.ipynb                         electron-quick-start                   kiezretter                             r                                      unity
a2                                     esade                                  leetcode                               ruby                                   valyria
ai2                                    express                                lime                                   rust
airflow                                fastapi                                lime.zip                               slap-countdown
archipinion                            finance                                lime_copy                              spiced_academy
blender                                fintech                                lotti                                  td

~/code
➜ git clone git@github.com:Robstaa/python_hello_world.git
Cloning into 'python_hello_world'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

~/code took 3s
➜ cd python_hello_world

python_hello_world on  master via 🐍 3.7.7
➜ python my_first_script.py
Type your name here: Robin
is this your name? Robin

python_hello_world on  master via 🐍 3.7.7 took 3s
➜ cd ..

~/code
➜ rm -rf python_hello_world

~/code
➜ cd cs101

cs101 on  master via 🐍 3.7.7
➜ ls
my_first_script.py

cs101 on  master via 🐍 3.7.7
➜ ls
my_first_script.py

cs101 on  master via 🐍 3.7.7
➜ cd ..

~/code
➜ ls
Alfred.Workflow.Todoist.alfredworkflow chrome-plugin-esade                    graph                                  ml                                     test-css
GamestonkTerminal                      cs101                                  hello                                  phaser                                 tindex_Lunar
Untitled Folder                        django                                 jordi                                  plurapolit                             tryhackme
Untitled.ipynb                         electron-quick-start                   kiezretter                             r                                      unity
a2                                     esade                                  leetcode                               ruby                                   valyria
ai2                                    express                                lime                                   rust
airflow                                fastapi                                lime.zip                               slap-countdown
archipinion                            finance                                lime_copy                              spiced_academy
blender                                fintech                                lotti                                  td

~/code
➜ mkdir code_from_friends

~/code
➜ cd code_from_friends

~/code/code_from_friends
➜ git clone git@github.com:Robstaa/python_hello_world.git
Cloning into 'python_hello_world'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

~/code/code_from_friends took 3s
➜ ls
python_hello_world

~/code/code_from_friends
➜ cd

~ via 🐘 v7.3.24
➜ cd code/code_from_friends

~/code/code_from_friends
➜ cd python_hello_world

python_hello_world on  master via 🐍 3.7.7
➜ python my_first_script.py
Type your name here: Robin
is this your name? Robin

python_hello_world on  master via 🐍 3.7.7 took 2s
➜ ls
my_first_script.py

python_hello_world on  master via 🐍 3.7.7
