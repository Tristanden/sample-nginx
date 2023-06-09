# sample-nginx

## To generate certs & keys 

`openssl req -key domain.key -new -x509 -days 365 -out domain.crt`

## To add users in the htpasswd file

```
sudo apt install apache2-utils
htpasswd -B .htpasswd user1
```

## To expose data on the internet

`ngrok http 8080`
