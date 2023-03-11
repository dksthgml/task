# task

## 과제방에 repo 주소로 업로드

1. task repository 포크로 본인 repository에 복사
2. 내려 받기해서 해당 README.md 문서 수정
3. 오늘까지 배운 git 내용 마크다운 형식으로 __잘__ 정리
  _markdown-cheetseat 참고_
4. 본인 repository에 업로드
5. 로컬 저장소 내용도 캡쳐해서 함께 업로드

이 아래로 내용 작성
-

​
-Github 

온라인 상에서 협업을 통해 버전 관리를 할 수 있게
해주는 대표적인 깃 호스팅 업체

-Bash

깃에서 사용할 수 있는 리눅스 쉘shell / 명령어


### git 설정부터 사용까지###
1. 로컬 저장소 만들기
2. 내 정보 등록, 로컬에 저장된 정보 변경, 로컬에 저장된 정보 삭제
3. 파일 추가 (파일은 미리 생성되어 있어야 함)
4. 메시지 작성과 함께 커밋-git commit -m "파일 설명" 
5. 이력 확인
-git log - 모든 커밋 이력 확인
-git log --oneline - 해당 라인 커밋 이력 확인
6. 현재 상태 확인- git status
7. add, commit 동시에( *두번째 커밋부터 사용 가능 )
-﻿git commit -am "파일 설명"
8. branch 만들기
﻿git branch dev
﻿git switch ﻿dev
git switch -c dev
﻿git branch -d dev﻿
git branch --list 혹은 git branch -a
9.  파일 및 폴더(디렉토리) 삭제 * git으로 지우지 않는 경우에도 사라진 파일들을 추적하지 않도록 한 번 더 git으로 지우는 작업이 필요 *
10. 복구 및 이전 커밋으로 이동
- git revert 123ab67 - 커밋 기록이 남아 권장
- git reset 123ab67 - 기록이 남지 않기 않기 때문에 회귀하기 어려움

#### github####
- github에서 내 저장소로 복사하기 git clone https://~
​- github에서 내 저장소로 복사하기(내 저장소에 폴더를 미리 만든 경우)
git clone https://~ . 주소 끝에 한 칸 띄어쓰기 후 마침표(.)


github에서 파일 내려받기
main 브런치- git pull (origin main)

다른 브런치- git pull origin 브런치이름
로컬 파일에 덮어 씌움

문서수정 후 커밋, push 
