# git & github 특강

- git init = 버전 관리 시작 = 내가 현재 있는 공간을 깃이 관리하는 마법의 폴더로 만들어줘! (절대 홈폴더에서 init X)

- git status = 현재 상황을 알려줘

- git add 파일명
  git add . = 현재위치 모두 무대로

- git commit -m "메시지"

  - git commit만 했을 때, VIM 진입
  - insert 모드 진입 -> i
  - 메시지를 기입한다
  - esc : 인서트 모드 탈출
  - wq (write and quit) (가능하면 VIM을 사용하지 말자)

- git log
  git log --oneline

- git checkout #값 해당 버전을 확인하기
  git checkout master 최근으로 빠져나오기

- git remote add origin <주소>

- git remote -v

- git push origin master

  수정→저장→add→commit 사이클 반복

- git init : 이 공간을 관리해줘

  vs

  git clone : 이 공간에 온라인 레포를 폴더째 들고와줘

  1. git init이 된 상태로 폴더를 가져와준다
  2. 그러니까 브릿지도 제대로 이어져있다 (주소가 이미 연결돼 있음)

- git init과 git clone은 단 한번

  vs

  push와 pull은 계속

- branch

  1. git branch = 확인하기
  2. git branch 브랜치명 = 생성하기
  3. git switch 브랜치명 = 이동하기 (git checkout 브랜치명 ←예전 명령어)
  4. git merge 브랜치명 = 합치기
  5. git branch -d 브랜치명 = 삭제하기 (강제삭제는 -D)

