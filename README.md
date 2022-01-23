# study-guide


### 스터디 기록 방식

- `git clone [레포지토리 주소]` 로 자신의 PC로 복제한다.

- `git branch` 현재 브랜치를 확인한다.

- `git checkout -b [브랜치 명]` 로 자신의 브랜치를 만듬과 동시에 브랜치로 이동한다.
  
  - `git checkout -b` 명령을 이용하면 만들고 이동이 동시에 이루어진다.

  - 참고
  
    - 하나하나 명령어로 진행해도 무관하다.

    - `git branch [브랜치 명]` : 브랜치 명으로 브랜치를 만든다.

    - `git checkout [브랜치 명]` : 브랜치 명으로 이동한다.

- `git branch` 로 다시 브랜치가 만들었는지 이동했는지를 확인한다.

- 자신의 브랜치에서 공부한 내용을 기록한다.

- `git add .` 명령어로 작업 디렉토리 상의 변경 내용을 스테이징 영역에 추가한다.

- `git commit -m "[기록 메시지 작성]" 개발 중인 코드의 이력을 만들 수 있다. 깃이 코드 변화를 기록한다.

- `git push origin [브랜치 명]` 브랜치 명을 지칭해 자신의 브랜치에 공부한 내용을 업데이트 한다.
