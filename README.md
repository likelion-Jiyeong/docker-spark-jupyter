# docker-spark-jupyter
도커로 스파크와 주피터노트북 설치 및 연동

# 패스워드 설정
'' 빈칸일 경우 비밀번호 없음
비밀번호를 넣고싶다면 암호화된 값을 넣어야함
암호화된 비밀번호 얻는 방법은 아래와 같음

컨테이너를 아래 동작법을 통해 시작한 후 아래 명령어를 실행한다. <br><br>
  ipython <br>  
  from notebook.auth import passwd <br>
  passwd() <br>
  Enter password: <br>
  please save the output password <br><br>
암호화된 비밀번호를 yml파일에 적어준다.(작은따옴표 있어야함!)

# 동작법
docker-compose.yml 파일이 있는 경로에서 
docker compose up 후 localhost:8891로 접속

 
 
