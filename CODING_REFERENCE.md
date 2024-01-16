#GIT

CHEAT-CHEAT - https://markdown.land/markdown-cheat-sheet

## GIT USEFULL COMMANDS

#### Start project in existing folder
====================================

```
git init
```

```
git add .
```

```
git commit -m <message>
```

```
git remote add origin https://github..com/Peter-Pear/<PROJECT_NAME>
```

```
git remote set-url origin git+ssh://git@github.com/Peter-Pear/<PROJECT NAME>
```

```
git push origin <branch>
```

### Merge to branch
===================

```
git checkout <NEW_BRANCH>
git merge <BRANCH>
```


# COMMAND LINE
==============


## GREP Usefull command line tips

```
grep --include=<Regex> -Rnw <FILE_PATH> -e <TEXT_PATTERN>

```
REGEX: \*.scss for only include scss files
FILE_PATH:  'src'
TEXT_PATTERN: '.p-tag' a class name example
