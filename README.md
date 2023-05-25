 # git command  개념 정리

- `git init`: git한테 이제부터 추적하라고 초기화 시켜주는 명령어
- `git remote add origin <remote repository url>`: git과 local(my computer)를 연결 시켜주고 해당 레파지토리를 앞으로 주소대신 Origin이라 부르겠다
- `git add <file name>`: 장바구니에 담듯 commit 전 중간 저장하는 명령어
- `git commit`: 장바구니에 담긴것들을 계산하는것과 같음
- `git push origin <branch name>`: origin(해당 레파지토리)에 내 브랜치를 올리겠다
- `git pull origin <branch name>`: origin에 있는 해당 브렌치를(보통 main) 내 로컬에 main으로 받아오겠다
- `git merge <branch name>`: Local main(아니면 다른 내 로컬 브랜치)에 있는것을 내가 현재 있는 local branch와 합치겠다
