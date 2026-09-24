## Машина загружается через BIOS, я ввёл команду ls /sys/firmware/efi и мне написало что данного каталога не существует 
~~~
liveuser@localhost-live :~ $ ls /sys/firmware/efi
ls: cannot access '/sys/firmware/efi': No such file or directory
~~~

## Таблица разделов
<img width="726" height="240" alt="image" src="https://github.com/user-attachments/assets/f9d6e842-4b14-446f-bd18-64f1ba1b39c7" />

(код плохо вставлялся,оставил так)

## Какое ядро работает на данный момент
~~~
liveuser@localhost-live :~ $ uname -r
6.19.10-300.fc44.x86_64
~~~

## Какие версии ядра установлены и доступны в меню
~~~
liveuser@localhost-live :~ $ ls /boot/vmlinuz -*
/boot/vmlinuz-0-rescue-4189730cf6c94d60bf67890447d58a3b
/boot/vmlinuz-6.19.10-300.fc44.x86_64


