### [< к содержанию](readme.md)

## git config

***Команда настройки параметров для Git на вашем компьютере.***

Для начала следует указать ваше имя и адрес электронной почты.

 Это важно, потому что каждый коммит в Git содержит эту информацию, и она включена в коммиты, передаваемые вами, и не может быть далее изменена:

```bash=
git config --global user.name "Your Name"
 
git config --global user.email "your_email@whatever.com"
```