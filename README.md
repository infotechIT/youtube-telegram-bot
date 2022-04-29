#Simple Telegram bot for searching first matching Youtube video
Call it with `/y search query here` ang wait for link to Youtube video.

#Installation
Clone repository, composer install, add config/prod.php with following parameters:

```
$app['telegram.token'] = '5319582868:AAEO4xBocch25cUNn4IRo8I-jbQH-XJqevw';
$app['youtube.key'] = 'AIzaSyBFaTikfmyFODSln7McWFUVbfU-YkKYmgE';
```

Setup webserver (with https), register bot with calling [setWebhook](https://core.telegram.org/bots/api#setwebhook) method
