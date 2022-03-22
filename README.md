# Git 的基本使用


## Step 1

先用command line(or terminal) cd到想要同步到Github的資料夾內<br>如下圖，若我想要同步的是IVTimer這個資料夾，在Mac的Terminal上就會是這樣

    (base) jaysun@sunyangzhedeMBP IVTimer % 
## Step 2
在確定有下載git後，輸入git init

    (base) jaysun@sunyangzhedeMBP IVTimer % git init
 
在我的例子裡，會輸入後會長這樣
```
(base) jaysun@sunyangzhedeMBP IVTimer % git init
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
Initialized empty Git repository in /Users/jaysun/Desktop/Swift/IVTimer/.git/
```
這時後可以

    (base) jaysun@sunyangzhedeMBP IVTimer % git config --global init.defaultBranch main
    
因為Github在創建new repository時是用main當default branch，又因為我在版控簡直是菜雞，所以我會先換成main
