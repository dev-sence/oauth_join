# discord-oauth-guilds.join
Discord Oauth2의 "Guilds.join" Scope를 활용한 코드입니다.

---

## .env.example과 config.py.example 내용 설명

### .env.example
```py
TOKEN=YOUR_TOKEN # 봇의 토큰을 입력해주세요.
OAUTH2_CLIENT_SECRET=YOUR_SECRET_KEY # 봇의 CLIENT_SECRET_KEY를 입력해주세요.
```

### config.py.example
```py
GUILD_ID = 1234567890 # 강제 초대할 서버의 ID를 입력하세요.
CLIENT_ID = 1234567890 # APPLICATION ID (BOT ID)를 입력해주세요.
REDIRECT_URI = 'http://localhost:5000/callback' # OAUTH 로그인 후 이동할 웹사이트의 주소를 입력하세요.
                                                # APPLICATION OAUTH 탭에서 REDIRECT URL을 http://[아이피]/callback으로 지정하세요!

# -- Sanic 호스트 설정 -- #
HOST = '127.0.0.1' # 127.0.0.1과 같이 수정해주세요.
PORT = 5000 # 포트를 지정해주세요.
```
