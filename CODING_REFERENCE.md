CHEAT-CHEAT - https://markdown.land/markdown-cheat-sheet


# NVIM

#### Select block of code
  - Hit **$** to go to the end of the lineover the {
  - Push **v** or **V** (depending on whether you want to select lines or not)
  - Push **%** (to jump to the matching bracket).

#### Html tag selection
  - select inner tag: **it**
  - select outer tag: **at**

#### Move to next/previous bracket/parenthesis
  - [( - Previous (
  - [{ - Previous {
  - [< - Previous <

  - [m - Previous method start
  - [M - Previous method end

  - ]} - Next }
  - ]) - Next )
  - ]> - Next >

#### Select paragraph VISUAL MODE
  - vip
  - vis
  - v35j/k - select from current line 35 lines down/up

#### Comment line/block of code
  - v -> gc

#### Redo
  - Ctrl + r


# GIT

#### Start project in existing folder

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

```
git checkout <NEW_BRANCH>
git merge <BRANCH>
```


# COMMAND LINE


## GREP
```
grep --include=<REGEX> -Rnw <FILE_PATH> -e <TEXT_PATTERN>

```
  - REGEX: \*.scss for only include scss files
  - FILE_PATH:  'src'
  - TEXT_PATTERN: '.p-tag' a class name example
