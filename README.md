# spring-event-demo

- spring에서 event를 publish 하고 listner에서 처리하도록 하는 로직 예제입니다.
- listner는 동기, 비동기, db 커밋이후만 실행 3가지로 나누어져 있습니다.

```bash
./gradlew bootRun

# 다른 터미널
curl -X POST "http://localhost:8080/api/users/signup?email=test@co.kr&name=YG"
```
