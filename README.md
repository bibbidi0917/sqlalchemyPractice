# DB 연결
1) 동일 워크스페이스에 'db_auth.py' 라는 파일을 생성한다.
2) 'db_auth.py' 파일에 아래와 같은 함수를 만든다. (info JSON의 값 부분은 사용자 환경에 맞게 조정 필요)
```
  def getConnectionInfo():
    info = {
      "username" : username,
      "password" : password,
      "host" : host,
      "port" : port,
      "db_name" : db_name
    }
    return(info)
```
