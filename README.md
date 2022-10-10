
## How to get start

```bash
./composer.phar install

```

#### Or visit the composer web site [here](https://getcomposer.org/).


## Exec command 

```bash
composer require phpmailer/phpmailer

```

#### to install the PHPMailer lib | or visit github.com/PHPMailer/PHPMailer;

<br>
### some things must be changed to continue and use the application

On xampp/app_send_mail/processa_envio.php
```properties
line 46: $mail->Host = 'insert your smtp host';
line 48: $mail->Username = 'insert your email addres'; 
line 49: $mail->Password = 'add your app password'; 

line 54: $mail->setFrom('your email', 'custom address');
``` 


