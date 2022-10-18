# Open Source sw
### 202234851 kangdoohyen 
---
### 내가 생각한 깃의 간단한 설명
깃은 컴퓨터 파일의 변경사항을 추적하고 여러 명의 사용자들 간에 해당 파일들의 작업을 조율하기 위한 분산 버전 관리 시스템이다. 
깃을 사용할 줄 안다면 깃을 사용하지 않는 것보다 훨씬 더 많은 사용자들 간에 파일 작업 조율이 원할하게 가능하다.
또한 중간에 새로운 브랜치를 만들어 기존에 만들어 놓은 코드를 놔두고 계속해서 새로운 방법으로 코딩에 도전할 수 있다. -> 실패하더라도 다시 원래의 코드로 돌아가면 그만이기 때문이다.

그 외에도 깃을 사용하는 것은 코드의 질 향상 및 많은 기능에 큰 도움을 준다.

---
| Git Command | function |
|---|:---:|
| `git init` | 이 파일을 깃으로 쓰겠다고 선언하는 느낌. |
| `git status` | 현재 깃 상태를 보는 커맨드 |
| `git add [file_name]` | 깃에다가 파일을 추가하겠다는 커맨드 |
| `git add .` | 깃에다가 지금까지 한거 전부 추가하겠다는 커맨드 |
| `git rm -cached [file_name]` | 깃에 추가한 커맨드 중 특정 파일을 지우겠다는 커맨드 |
| `git ignore` | 깃에 올리고 싶지 않은 파일을 무시해라는 키워드 |
| `git log` | 이 때까지 적은 깃 로그를 보기 |
| `git branch` | 깃 브랜치 생성 |
---
## Tips for Git
### ***Start git***
깃 시작할 때 처음에 1회만 사용하면 되는 코드
```sh
$ git config --global user.name "[name]"
$ git config --global user.email [email]
$ git config --global init.defaultBranch main
```
---