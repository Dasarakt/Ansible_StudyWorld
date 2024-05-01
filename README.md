# Ansible_StudyWorld
Ansible.
https://www.softether-download.com/en.aspx?product=softether - VPN сервер.
Написать плейбук и все сопутствующие роли для реализации следующий задач:
1) установка vpn сервера
2) запуск vpn сервера
3) конфигурирование vpn сервера:
а) создать указанный список VirtualHub
- PROD
- TEST
- STAFF
б) в каждом VirtualHub создать список пользователей:
PROD:
pr_user1
pr_user2
TEST:
t_user1
t_user2
в) STAFF
ceo
cto
admin
Доп. требования:
- нужно пользоваться JSON API: https://github.com/terassyi/go-softether-api
- хабы не должны быть видны анонимно (no enumerate)
- в ролях использовать зависимости (роль по конфигурированию должна подтягивать за собой роль по установке)
