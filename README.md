## **Freep** is an open source upload center that store your file on **Telegram** without expiration.

##### requirements
1. Go installed on your machine.
2. Build [telegram-bot-api](https://tdlib.github.io/telegram-bot-api/build.html) ( Optionals if you want to up/dow up 2GB and 4GB if you are a premium user. )
3. a .env files **You can find necessary envs from .env.example file**

##### Installation

```
git clone https://github.com/r3a70/freep.git
cd freep && go build . && ./frp
```
Then your server starting on :8000.

#### Task lists
- [ ] Read ip, port and ssl-certs from command line.
- [ ] Dockerization.
- [ ] Replace third-party telegram lib with Self-Write lib.
