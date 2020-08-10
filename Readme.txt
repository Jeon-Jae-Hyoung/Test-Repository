git init  // .git 생성

git remote add origin (repository address) 깃 주소
git status  //보낼 파일 상태
git add . // 적용이 안된 파일 깃으로 업데이트
git commit -m "message" // 커밋하고 메세지 
git push origin master //최종 파일올리기

상대파일 가져오기
git init remote add origin (repository address) 깃 주소
git pull origin master    ///  상대방 파일 가져오기
git status
git add .
git commit -m "second commit"
git push origin master

git config --global user.email "이메일주소"

git config --global user.name "이름" 을 입력하여 설정시켜줍니다.