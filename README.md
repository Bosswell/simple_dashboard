<h1>Zadanie 2</h1>

1. Komendy do postawienia środowiska

```console
$ docker-compose up
$ docker exec -it simple_app bash
$ php bin/console doctrine:database:create
$ php bin/console doctrine:migration:migrate
$ php bin/console doctrine:fixtures:load
```

Strona domyślnie powinna działać pod adresem:
http://localhost:8080

W wytycznych do zadania nie było mowy o roli admina do deaktywacji kont, w takim razie każdy użytkownik może deaktywowac pozostałe konta :)

<b>Domyślne dane:</b> <br>
Username: Administrator <br>
Password: haslo123
