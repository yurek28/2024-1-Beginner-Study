## What I Learnd
2024/4/2 세 번째 개발 입문 스터디

git log 명령어를 사용하여 commit id, head(현재 작업중인 위치) 등을 확인 가능

commit 메시지를 수정하고 싶을 때는 commit --amend 명령어 사용

reset vs revert

- reset 

soft, mixed, hard의 3가지 옵션이 존재함 

soft: staging area로 되돌리기

mixed: default값이며 working directory로 되돌리기

hard: 변경 사항을 모두 제거하기

reset의 경우 3가지 옵션 모두 commit을 제거하기 때문에 위험함

- revert 

reset과 달리 commit을 제거하지 않고 되돌리기

안전하게 commit을 제거하지 않는 revert를 쓰도록 하자
