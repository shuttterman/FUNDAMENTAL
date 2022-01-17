# FUNDAMENTAL

# Web

예전에는 단순히 정보를 보여주는 것에 그쳤다면 현재는 많은 서비스를 웹을 기반으로 제공하고 있음 → 웹에서 처리하는 정보 자산들이 많아짐에 따라 이들을 안전하게 보관하고 처리해야 할 필요성이 증가함

### Status code, reason phrase

- 1xx: Information
- 2xx: Success(e.g. 200: 성공)
- 3xx: Redirection(e.g. 302: 다른 URL로 갈 것)
- 4xx: Client error(e.g. 400:요청이 문법에 맞지 않음, 403: 클라이언트가 리소스에 요청할 권한이 없음, 404: 리소스가 없음)
- 5xx: Server error(e.g. 500: 요청을 처리하다가 에러가 발생함, 503: 서버가 과부하로 인해 요청을 처리할 수 없음)

### 웹의 통신과정

1. (Client) 이용자가 브라우저를 이용해 웹 서버에 접속
2. (Client) 브라우저는 이용자의 요청을 해석하여 HTTP 형식으로 웹 서버에 리소스를 요청
3. (Server) HTTP로 전달된 이용자의 요청을 해석
4. (Server) 해석한 이용자의 요청에 따라 적절한 동작
5. (Server) 이용자에게 전달할 리소스를 HTTP 형식으로 이용자에게 전달
6. (Client) 브라우저는 서버에게 응답받은 HTML, CSS, JS등의 웹 리소스를 시각화하여 이용자에게 보여줌