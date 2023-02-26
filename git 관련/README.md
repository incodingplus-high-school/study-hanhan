## 깃허브 터미널 명령어 정리

#### SETUP
``
git config --global user.name [firstname lastname]``
사용자 정보

``
git config --global user.email [valid-email]``
이메일 주소

``
git config --global color.ui auto``
Git에 대한 자동 명령줄 색상 설정

#### SETUP & INIT

``
git init``
기존 디렉터리를 Git 저장소로 초기화

``
git clone [url]``
주소 clone

#### STAGE & 

``
git status``
Git 프로젝트의 상태를 확인

``
git add [file]``
선택한 파일을 다음 커밋떄 추가

``
git reset [file]``
작업 디렉터리의 변경 사항을 유지하면서 파일 스테이징 해제

``
git diff``
Repository와 Working Directory 사이의 다른점을 보여준다

``
git diff --staged``

``
git commit -m [descriptive message]``