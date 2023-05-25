## Git Command

- `git init` : 이제부터 이 파일을 추적하겠다는 뜻. 최초에 한번만 해준다.
- `git remote add origin <remote repository url>` : 기존 워킹 디렉토리에 새 리모트 저장소를 쉽게 추가할 수 있는데
  git remote add '단축이름(origin)' 'remote repository url' 명령을 사용한다.
- `git add <file name>` : 다음 변경(commit)때까지 변경분을 모아놓는다.
- `git commit` : add한 파일들을 저장소에 기록한다.
- `git push origin <branch name>` : git이 현재 브랜치'를' push한다. 원격(origin)의 브랜치이름으로.
- `git pull origin <branch name>` : git이 현재 브랜치'로' pull한다. 원격(origin)의 브랜치이름으로.
- `git merge <branch name>` : 현재 checkout된 브랜치로 `<branch name>`을 병합한다.
