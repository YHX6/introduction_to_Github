# Github Introduction

## 1. Github workflow

![image-20220922140534213](C:\Users\xyh10\Desktop\ISB\classes\INFO 5001\img\image-20220922140534213.png)

## 2. set config

```git
// set config
git config --global user.name "Yaohong"
git config --global user.email "xiang.yao@northeastern.edu"

//check config
git config --global user.name 
git config --global user.email 
```

git configuration levels:

(1) system: for all the users on this computer

(2) global: apply to that user account

(3) local: single repository level

## 3 clone to local

```
// 1.clone the project into local repository
git clone https://github.com/YHX6/introduction_to_Github.git

//2.enter the pj
cd introduction_to_Github

//3.make a branch called "my-branch"
git branch my-branch

//4.check all the branches
git branch --all 

//5.push to github
git push --set-upstream origin my-branch
```

![image-20220922144252342](C:\Users\xyh10\Desktop\ISB\classes\INFO 5001\img\image-20220922144252342.png)

## 4. make a commit and push to github

```
// 1.enter the branch
git checkout my-branch

// 2. check which branch we are cuurently at
git status 

//creating files

// 4. add the file and commit
git add test.md
git commit -m "demarcia"
git push
```

![image-20220922145539193](C:\Users\xyh10\Desktop\ISB\classes\INFO 5001\img\image-20220922145539193.png)

![image-20220922145359604](C:\Users\xyh10\Desktop\ISB\classes\INFO 5001\img\README.md)



**why we need "git add" before "git push"?**  three stages

![image-20220922145815126](C:\Users\xyh10\AppData\Roaming\Typora\typora-user-images\image-20220922145815126.png)

## 5. pull request