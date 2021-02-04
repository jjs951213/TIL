# git 기초

> 분산버전관리 시스템(DVCS)

## 0. git저장소(repository) 초기화

```bash
$ git init
Initialized empty Git repository in C:/Users/j1oab/Desktop/md/.git/(master) $

```

* `.git` 숨김폴더가 생성되고, bash 환경에서는 `(master)` 로 브랜치 정보가 나타난다.

## 작업 흐름

### 1.`add` 

``` bash
$ git add . 			# . 현재디렉토리
$ git add a.txt b.txt	# 특정파일
$ git add myfolder/		# 특정 폴더
```



현재 작업 중인 파일의 변경사항을 `staging area` 로 변경한다.

* staging area : 커밋(버전)으로 기록할 대상의 파일들의 목록







### 2. commit 

> 변경사항들을 버전으로 기록

* 특정시점을 스냅샷처럼 기록한다
* commit시 메세지는 반드시 잘 작성해야한다
  * 지금 기록한 코드의 이력을 나타낼수 있도록



## 기타 명령어

### log

``` bash
$ git log
commit 1e83e5174b5426ade9317769d823dbea82a61e9d (HEAD -> master)
Author: jjs951213 <jjs951213@naver.com>
Date:   Thu Feb 4 14:11:27 2021 +0900

    First commit
$ git log --oneline #한줄로
1e83e51 (HEAD -> master) First commit
$ git log -2 #최근2개
$ git log --oneline -1 #최근 1개를 한줄로
```

### status

```bash
$ git status

```



