Today I learned

1. 간단한 명령어

- pwd : 현재 위치가 어딘지 알고 싶을 때
- ls : 현재 위치의 디렉토리 조회
- cd 디렉토리명 : 해당 디렉토리로 이동
- mkdir 디렉토리명 : 디렉토리 생성
- touch : 파일 생성
- mv : 파일 위치 옮기기
- cp : 파일 복사

2. Vim

- vi 파일명 : 파일 작성
- i를 눌러서 insert 상태로 만들어서 작업 가능
- 작업이 완료 됐다면 esc후 :wq로 저장
- ctrl + c : 뭔가 잘못됐을 때 작업 중단

3. commit

- commit은 일종의 세이브 포인트
- vi ~/.gitconfig : 깃 설정을 보고 변경할 때 사용
- git status : 현재 상태 확인할 때
- git add 파일명 : 커밋 전 파일을 로컬에서 임시로 저장?
- git commit : add를 통해 임시 저장한 파일을 github에 올릴 준비 완료 시키기?
- git push : 커밋한 파일들을 github에 전송시키기?
- commit을 했을 때, 첫 줄은 commit의 제목을 작성한다. 이때 다른 사람도 알기 쉽게 간단 명료하게 작성해야 한다.
- 마크다운인 #의 갯수가 적을 수록 더 큰 의미?를 가진다.
- commit의 제목은 구, 절로 해야한다.

4. gitignore

- git이 특정 파일이나 폴더를 버전 관리에서 제외하도록 지정한 설정 파일이다.
- gitignore에적힌 파일과 폴더는 git이 track하지 않아서 커밋, push할 때 올라가지 않는다.

5. branch

- main가지에서 뻗어 나와 따로 작업할 수 있는 가지를 만드는 행위
- branch를 통해 실무에서 작업한 내용을 지우거나 되돌릴 때, 편하게 작업이 가능하다.
- git branch : 브런치 목록 보기
- git branch 이름 : 브런치 생성
- git switch 브런치명 : 브런치로 이동
- git merge : 브런치 병합
- 브런치는 머지 했다면 가지는 제거해줘야 한다.

참고. git status는 습관적으로 하라.
