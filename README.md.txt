### README.md

- 반갑습니다.
- 테스트를 따라하는 중입니다.
- README.md 에는 간단한 소개 또는 설명글을 작성하시면 됩니다.

- 내용수정 테스트 1
- 내용수정 테스트 2 - 복습 :  add 에서 README.md 파일만 따로 했는데 인식을 못함 그래서 * 사용
			명령어 중에서 status 가 어색함
			git commit -m 을 git commit m- 입력해서 오류발생
git add * > git status > git commit -m > git push origin master

- 내용수정 테스트 3 - 파일 추가하기 : 기존에 README 이외에 add file 이라는 txt를 저장해서 add * 를 사용하여 전부 스테이징 영역에 넣은뒤 status 로 파일 상태를 확인후 git commit -m을 통해 로컬저장소에 옮기고 
		   git push origin master 를 통해 원격 저장소에 옮김
홈페이지에서는 커밋 횟수와 브랜치 정보를 확인할수 있다.
이때 기본적으로 master 브랜치가 자동 생성된다.
따라서 git push origin master 의 이유도 기본으로 생성된 master 브랜치를 사용하기 위해서이다.
- 내용수정 테스트 4 - 파일 삭제해보기 테스트 3에서 추가한 add File.txt 를 삭제하고 commit 해보자
- 내용수정 테스트 5 - 테스트 4에서 commit 을 했을때 파일을 없으면 그파일은 삭제될까 했지만 그것은 아니였다. 테스트를 진행하고 생각해보니 이미 파일은 github에 올라가 있기 때문에 여기서 파일을 삭제한다 해도 파일은 삭제되지 않는다.
			즉 git을 이용해서는 수정, 추가 밖에 할수 없는것 같다 아니면 삭제하는 방법을 내가 아직 모르는것 같기도 하다.
- 내용 테스트 보기 숨겨진 폴더 찾아서 집어넣기
This is an H1

21-06-06 2일차 파일 업로드 복습