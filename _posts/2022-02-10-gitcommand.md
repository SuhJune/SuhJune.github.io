---
layout: post
title: Git command
date: 2022-02-10 22:19 +0800
tags: [learning,git]
toc: true
---
<h2>Git command
<h1>Git
<h3>Git이란?

<h5>Git이란 souce 관리를 위한 분산 전 관리 시스템이다. 최초로 리눅스 토발즈가 리눅스 커널 개발에 이용하려고 개발하였습니다.

---
<h3> git add

```
git add <파일 이름>
git add *
```
---
git commit
```
git commit -m"이번 확정본에 대한 설명"
```
---
git push
```
git push origin master
git remote add origin <원격 서버 주소>
```
다른 명령어
```
git init : git 생성하기
git clone git_path : 코드가져오기
git checkout branch_name : 브랜치 선택하기
git checkout -t remote_path/branch_name : 원격 브랜치 선택하기
git branch branch_name : 브랜치 생성하기
git branch -r : 원격 브랜치 목록보기
git branch -a : 로컬 브랜치 목록보기
git branch -m branch_name change_branch_name : 브랜치 이름 바꾸기
git branch -d branch_name : 브랜치 삭제하기
git push remote_name — delete branch_name : 원격 브랜치 삭제하기 ( git push origin — delete gh-pages )
git add file_path : 수정한 코드 선택하기 ( git add * )
git commit -m “commit_description” : 선택한 코드 설명 적기 ( git commit -m “내용”)
git push romote_name branch_name : add하고 commit한 코드 git server에 보내기 (git push origin master)
git pull : git서버에서 최신 코드 받아와 merge 하기
git fetch : git서버에서 최신 코드 받아오기
git reset — hard HEAD^ : commit한 이전 코드 취소하기
git reset — soft HEAD^ : 코드는 살리고 commit만 취소하기
git reset — merge : merge 취소하기
git reset — hard HEAD && git pull : git 코드 강제로 모두 받아오기
git config — global user.name “user_name ” : git 계정Name 변경하기
git config — global user.email “user_email” : git 계정Mail변경하기
git stash / git stash save “description” : 작업코드 임시저장하고 브랜치 바꾸기
git stash pop : 마지막으로 임시저장한 작업코드 가져오기
git branch — set-upstream-to=remote_path/branch_name : git pull no tracking info 에러해결
```