`main`  `master`  `develop`

# Contents
1. Git 명령어
2. 사용하기
3. 참고 사이트

<hr />

## 1. Git 명령어 (Commit, Push, Pull, Branch, Merge)

추가와 확정(Commit) 

    git add -A
    git commit -m '{comment content}'

변경된 내용 반영 

    git push 
    git push origin {branch name}

    git add origin {URL} git push -u origin master

가지치기 

    git branch {branch name} 
    git branch -d {branch to be deleted} 
    git checkout -b {new branch name} 
    git checkout {branch name}

    remote repository
    git remote

갱신

    git pull 
    git merge {merge branch name}

 조회 및 변경
 
    git log 
    git revert {git log-first 6 numbers}
    git restate --hard
    git rebase {branch name}
    
현재 상태

    git status

    git clone {git repository URL}
    

<hr />

## 2. 사용방법

vscode - terminal
sourceTree

<hr />

## 3. 참고 사이트 ( HICC)

  [동빈나의 깃허브 유튜브 영상](https://youtube.com/playlist?list=PLRx0vPvlEmdD5FLIdwTM4mKBgyjv4no81)
  [얄팍한 코딩사전 유튜브](https://www.youtube.com/watch?v=FXDjmsiv8fI)
  [마크다운 사용방법](https://gist.github.com/ihoneymon/652be052a0727ad59601)
  [Git 간편 안내서](https://rogerdudler.github.io/git-guide/index.ko.html)
  [Git 연습할 수 있는 사이트](https://learngitbranching.js.org/?locale=ko)
  
  [GIT1 - 생활코딩 및 SourceTree 코스 추천 (총 4시간)](https://www.opentutorials.org/course/3837)
  [생활코딩 - GitHub.com](https://www.youtube.com/playlist?list=PLuHgQVnccGMDWjb0TWItMCfDWDs8Y3Oo7)
  
  
  
  
<hr />

### 과제 내용

- [X] 자기 GitHub 계정에 public Repository 생성 `hicc-practice`
- [ ] git clone해서 로컬 저장소 생성 (이후 과정은 로컬 저장소에서 진행) `git clone {url}`
- [X] develop branch를 만들고 checkout `git checkout -b develop`
- [X] Git에 관해 학습한 것들을 README.md파일에 정리해서 커밋
- [X]  여러 번에 나눠서 커밋해도 되고 한 번에 커밋해도 됨 `git add -A / git commit -m {content} `
- [X] 원격 저장소로 push `git push`
- [X] master branch로 merge 후 push `git branch master / git merge develop `
- [ ] 또는 가능할 경우, 원격 저장소(GitHub)에서 Pull Request를 올린 뒤 merge

<hr />

END.
