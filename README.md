# Run n8n + [WAHA](https://github.com/devlikeapro/waha) for free
Use n8n + [WAHA](https://github.com/devlikeapro/waha) for free and run it locally on your device!

## How to do so 🤔?
there are 2 ways:

1- As stated in [n8n](https://github.com/n8n-io/n8n) by using `npx` and running the below commnad:
```
npx n8n
```

2- Or by using `Docker` in which we are going to explain all the steps below:
* Clone this repo or download the code
* Navigate to the project directory and run:
```
docker compose up
```

That's it!

**Don't forget to download [ngrok](https://ngrok.com/download) and run the below whenever you are using Webhook node:**
```
ngrok http 5678
```
