# ovpn_install.sh
CentOS v7 install openvpn

Скрипт скачется, запустится и начнет задавать вам вопросы и комментировать свои действия на русском языке. Вам останется лишь читать и отвечать на вопросы скрипта. После установки OpenVPN скрипт перзагрузит сервер. После этого можете заходить с помощью WinSCP и скачивать из папки /root/ файл(ы) .ovpn с уже «вшитыми» в них сертификатами. Дальше применяете их

Для установки прозрачного прокси-сервера 3proxi
запустите скрипт командой
bash /root/ovpn_install.sh
и выбирайте нужный пункт меню. В том же меню вы можете создать новых пользователей или удалить уже имеющихся.
