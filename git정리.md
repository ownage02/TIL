1. git init = 버전 관리 시작 = 내가 현재 있는 공간을 깃이 관리하는 마법의 폴더로 만들어줘! (절대 홈폴더에서 init X)
2. git status = 현재 상황을 알려줘
3. git add 파일명
  git add . = 현재위치 모두 무대로
4. git commit -m "메시지"
  1. git commit만 했을 때, VIM 진입
  2. insert 모드 진입 -> i
  3. 메시지를 기입한다
  4. esc : 인서트 모드 탈출
  5. :wq (write and quit) (가능하면 VIM을 사용하지 말자)
5. git log
  git log --oneline
6. git checkout #값 해당 버전을 확인하기
  git checkout master 최근으로 빠져나오기
7. git remote add origin <주소>
8. git remote -v
9. git push origin master
  수정→저장→add→commit 사이클 반복