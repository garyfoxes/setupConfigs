# setupConfigs

# ADB COMMANDS
emulator -avd Android4 -dns-server 8.8.8.8

adb install < path_to_apk_file> (installs apk to device or emulator)

adb shell pm list packages(gets all package names on your device)

adb shell pm path com.whatsapp(gets the path of the apk on the device)

adb pull /data/app/com.whatsapp-21.apk C:\Users(copies apk to your laptop at a specified destination)

adb kill-server
adb start-server

#GIT COMMANDS

git checkout (branch name)
git branch myname
git checkout -b feature-fix_minigame_test 
git pull origin master

git add *.java
git commit --amend -m "Fix this "
git commit -m "commit mnessage"

PUSHING
git push -f origin feature-fix_minigame_test

MERGE??
git merge --no-commit feature-fix_minigame_test master


Amending Previous commit
Stage the extra changes like would for a normal commit

git add .
Then just commit with the --amend argument
git commit --amend
git diff [the changed file]

DELETE BRANCH LOCALLY
git branch -D (branch name)

Change Branch Name
git branch -m <oldname> <newname>

DELETE BRANCH REMOTELY
git push origin --delete <branchName>

Check Config List
git config --list

Set Remote Url
git remote set-url origin git://new.url.here

