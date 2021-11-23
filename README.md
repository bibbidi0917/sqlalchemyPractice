# DB 연결
1) 홈디렉토리에 '.sqlalchemy' 폴더를 만든다.
2) '.sqlalchemy' 폴더 안에 'config.yaml' 파일을 생성한 후 아래와 같이 DB 정보를 세팅한다. 
    (사용자 환경에 맞게 우측의 value 부분을 세팅해야 함)
```
username: username
password: password
host: host
port: port
db_name: db_name
```

# problem1 : 자료 엑셀파일 경로
1) 홈디렉토리의 '.sqlalchemy' 폴더 안에 '인구통계.xlsx', '한국인이름.xlsx' 파일을 넣는다.