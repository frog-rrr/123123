#REAMDE
# Install
. Git
.DB Browser for SQLite

# Linux command
mkdir [folder.name] #create new folder in currnet directory
cd [folder.name] # go to next level folder in 

# Initialize Environment
in terminal:
. git --version
. git config --global user.name 'frog-rrr'
. git config --global user.email 'lnianen93@gmail.com'
. git init

# Common Used Instruction
. git status
. git log --oneline

# track file and Folder
. git add[full file name]
. git add *.file_sub_name
. git add .
. git commit -m 'message'

# Regular Process
. git add .
. git commit -m 'messsage'
. git push

# Supplementary: other instruction of modify file
. git reset --soft HEAD~ #回到上一動/canceling commit
. git reset --hard [version.number]
. git diff [version.number] -- [filename]
. git checkout [version.num] -- [filename]