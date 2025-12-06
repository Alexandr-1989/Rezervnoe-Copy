Задание 1\
Составьте команду rsync, которая позволяет создавать зеркальную копию домашней директории пользователя в директорию /tmp/backup \
Необходимо исключить из синхронизации все директории, начинающиеся с точки (скрытые)\
Необходимо сделать так, чтобы rsync подсчитывал хэш-суммы для всех файлов, даже если их время модификации и размер идентичны в источнике и приемнике.\
На проверку направить скриншот с командой и результатом ее выполнения\
<img width="996" height="368" alt="Screenshot_2" src="https://github.com/user-attachments/assets/6e5fdea6-30a2-4853-9763-de3695f16e2e" />
<img width="888" height="780" alt="Screenshot_1" src="https://github.com/user-attachments/assets/fda7c85d-52c4-4611-8f5d-5a648586d321" />

Задание 2\
Написать скрипт и настроить задачу на регулярное резервное копирование домашней директории пользователя с помощью rsync и cron.\
Резервная копия должна быть полностью зеркальной\
Резервная копия должна создаваться раз в день, в системном логе должна появляться запись об успешном или неуспешном выполнении операции\
Резервная копия размещается локально, в директории /tmp/backup\
На проверку направить файл crontab и скриншот с результатом работы утилиты.\

[Crontab](https://github.com/Alexandr-1989/Rezervnoe-Copy/blob/main/files/Crontab)

<img width="677" height="73" alt="Screenshot_3" src="https://github.com/user-attachments/assets/74b933fa-0536-4a2e-ab17-de78ab4042cd" />
<img width="874" height="524" alt="Screenshot_6" src="https://github.com/user-attachments/assets/863d6dbc-f497-4b8b-b3b9-621256e9652c" />
<img width="883" height="545" alt="Screenshot_5" src="https://github.com/user-attachments/assets/1a31304a-9488-4da3-9590-4997a1aeac2b" />
