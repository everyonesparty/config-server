### Github Private Repository 를 통해 설정관리하기
* 참고
  * https://oingdaddy.tistory.com/188
  * 여기서 `직접 git 계정을 입력해 https로 가져오는 방법` 을 사용
    * github 비번은 access_token 으로 사용(최근 github 의 정책 변경으로..)
    
### 혹시 application.yml 파일의 특정 상수를 변수처리하고 실행시 이를 외부에서 입력하도록 할 수 있나?
* 참고
  * https://kim-jong-hyun.tistory.com/99
* 이게 되면 github access_token 부분을 실행 시 외부에서 입력하도록 할 수 있을듯
* config-server 의 application.yml 파일의 github 계정 비번 부분을 변수처리함!
  * 해당 부분은 vm option 으로 외부에서 실행 시 입력해 줘야 설정정보를 받아올 수 있음
  




