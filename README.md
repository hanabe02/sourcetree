# sourcetree 정리

## 1. 충돌 오류 발생
   
** test1, test2 유저가 있음**
1. **test1**
   - 유저가 orderRegistForm.vue 파일 수정
   - main 병합 push
   - **error 안나고 정상적으로 완료됨**
   - bitbucket 제대로 반영된 것을 확인
     
2. **test2**
   - orderRegistForm.vue 파일 수정
   - main 병합 성공 push
   - error 발생 : 브런치가 main 브런치보다 앞서는 문제가 발생!!
   - + 추가로 pull 이 생겨서 main 브랜치에서 데이터를 당겨오니
   - 원격 main 과 main 브랜치의 변경점이 달라서 발생하는 문제
  
