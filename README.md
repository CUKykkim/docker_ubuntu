# 클라우드 기반의 도커 실습 환경 가이드

- 본 가이드는 로컬 환경에서 도커를 설치하지 못하시는 분들을 위해 작성이 되었으며, 실습 환경은 서로 공유될 수 있습니다. 
  실습환경의 비밀번호는 강의실에서 확인하시면 됩니다.


## Windows Terminal 실행

- 아래와 같이 Windows Terminal을 실행하여 ssh 접속 명령어 입력 실습 서버에 연결합니다. 

  * 1번 서버

    ```
    ssh -p 63615 globus@211.237.9.166
    ```


- 비밀번호 입력 후 우분투 접속

  ![docker_cloud](./images/docker_cloud.png)


- 클라우드 실습시 주의 사항

  * 실습 환경을 타 학생과 공유 하므로, 실습이 끝나고 난 뒤 반드시 자신이 수행중인 컨테이너를 삭제할 것!!!!!
    + 삭제 예 : docker rm -f $(docker ps -aq)
      
      ![remove](./images/remove.jpg)