# ДЗ №2 — Безопасность Linux

Студент: 370498.

| Файл | Раздел | Что выполнено |
| --- | --- | --- |
| [mephi-screenshot.png](mephi-screenshot.png) | 7, 8 | Страница nginx с текстом `Hello from Student: 370498`. |
| [history.out](history.out) | Все | История выполненных команд. |
| [ping.out](ping.out) | 1 | Проверка связи с `8.8.8.8`: 4 ответа, потери 0%. |
| [dnf.out](dnf.out) | 2 | Обновление системы, установка nginx и libcap-ng-utils. |
| [stat.out](stat.out) | 3, 5 | Каталог проекта: `root:students`, права `2770`. Каталог `/mephi-web`: права `0755`, контекст `httpd_sys_content_t`. |
| [journalctl.out](journalctl.out) | 4 | Журнал запуска и перезапуска nginx. |
| [getcap.out](getcap.out) | 5.2 | Для tcpdump установлены `cap_net_admin,cap_net_raw=eip`. |
| [getenforce.out](getenforce.out) | 5.3 | SELinux в режиме `Enforcing`. |
| [curl.out](curl.out) | 7 | Ответ сервера: `Hello from Student: 370498`. |
| [fstab](fstab) | 3 | Монтирование ext4 с меткой `MEPHI_WEB` в `/mephi-web`. |
| [passwd](passwd) | 5.1, 6.1 | UID разработчиков: `5501`, `5502`, `5503`. У кураторов оболочка `/sbin/nologin`. |
| [shadow](shadow) | 6.2 | Срок действия паролей — 90 дней, предупреждение — за 7 дней. Хеши скрыты. |
| [group](group) | 5.1 | Разработчики входят в `students`, кураторы — в `curators` с GID `4444`. |
| [pwquality.conf](pwquality.conf) | 6.2 | Минимальная длина пароля — 12 символов. |
| [acl.out](acl.out) | 5.1 | Разработчикам доступны чтение и запись, кураторам — чтение, остальным доступ закрыт. Настроено наследование ACL. |
| [users-check.out](users-check.out) | 5.1 | Проверка UID и групп участников проекта. |
| [tcpdump-check.out](tcpdump-check.out) | 5.2 | Проверка tcpdump от `user1`: захвачен один пакет. |
