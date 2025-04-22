wd : directory

ls : 디렉토리 확인

ls -a : 모든 숨김파일까지 확인

ls -l : 디렉토리 한줄씩 보기

ls -al : 모든 숨김파일 한줄씩 보기

cd : change directory // ex : cd Documents

cd .. : 상위 디렉토리로 이동

## 입력 후 TAB 클릭 시 자동완성

mkdir  : make directory

touch : make file

mv : 파일 이동 — move // ex : mv readme.txt bin

mv 파일이름.* 이동목적지 : 모든 확장자 파일 이동 (같은 이름의 파일 존재시 덮어씌우기됨)

mv  **.**x 이동 목적지 : x로 끝나는 파일 전체 이동

cp : 파일 복사 

cp main.c ./main_copy.c // 같은 이름 복사 시 이름 변경 후 복사가능

rm : 삭제

rm -rf docs ( r은 디렉토리 삭제 f는 묻지말고 걍 삭제시켜 )



vim

vi or vim 파일명 : 파일 열기

cat 파일명 : 내용 확인하기



git

git status : 상태 변화가 있는지 확인하는 명령어

git add : 파일 추가

git commit : 커밋

## 성공한다면 : 



[main 4b1fa88] My first commit

1 file changed, 1 insertion(+)

create mode 100644 [main.py](http://main.py/)



## 라는 문구 입력됨



git log : 지금까지 커밋한 내역 및 커밋 로그 확인가능

git push origin main : git에 올리깅~



## 내 프로필 설정 링크

https://rahuldkjain.github.io/gh-profile-readme-generator/



git branch — 브랜치 확인

git branch -a or -r 브랜치 확인

git remote  어떤 리모트로 가져왔는지

git remote -v  주소

git switch 브런치 이름

git merge 합칠 브런치 이름



## 브런치 생성 → 브런치 스위치 → 작업 → 이상없으면 저장 후 브런치 메인으로 스위치 → 브런치 메인에서 머지

## 모든 작업 완료된 브런치는 삭제 ——→ git branch -D 브런치 이름


