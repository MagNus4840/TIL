### 원격 저장소 연결

```
git remote add origin https://github.com/MagNus4840/TIL.git
```



### 원격 저장소 연결 여부 확인

```
git remote -v

origin  https://github.com/MagNus4840/TIL.git (fetch)
origin  https://github.com/MagNus4840/TIL.git (push) 
```



### 원격 저장소로 보내기

```
$ git push origin master
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 738 bytes | 738.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/MagNus4840/TIL.git
 * [new branch]      master -> master
```



