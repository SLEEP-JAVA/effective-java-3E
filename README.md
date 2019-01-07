# 작성 방법 

1. 저장소를 clone 받는다. 
2. master branch 에서 시작한다.
3. `npm install gitbook-cli -g` 로 글로벌에 gitbook-cli를 설치한다. 
4. md파일로 정리를 작성한다. 
5. 파일을 모두 작성하면 summary.md에 양식에 맞추어 자신의 글을 목록에 추가한다. 
6. `chmod +x publish_gitbook.sh` 로 스크립트 실행권한을 얻은 뒤 `./publish_gitbook.sh` 로 퍼블리시 완료 
7. 끝!

## 주의사항

그냥 commit push 하면 꼬이니까 그냥 스크립트를 이용하도록 하자
