ubuntu-nginx-php-ssmtp
=============

nginx with PHP and configurable sSMTP based on efaille/nginx-php-ssmtp and mkaag/phpfpm

## Usage
```bash
docker run -d \
-e "SMTP_HOST=mail.domain.com:587" \
-e "SMTP_DOMAIN=domain.com" \
-e "SMTP_TLS=YES" \
-e "SMTP_STARTTLS=YES" \
-e "SMTP_USERNAME=username" \
-e "SMTP_PASSWORD=password" \
-p 80:80 \
panderpeter/ubuntu-nginx-php-ssmtp
```

## Compose
I've added a compose file for easier usage. Check it out from my repo.

