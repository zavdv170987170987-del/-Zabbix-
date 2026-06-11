# -Zabbix-
Домашнее задания "Система мониторинга Zabbix"

### Задание 1 

Установите Zabbix Server с веб-интерфейсом.

#### Процесс выполнения
1. Выполняя ДЗ, сверяйтесь с процессом отражённым в записи лекции.
2. Установите PostgreSQL. Для установки достаточна та версия, что есть в системном репозитороии Debian 11.
3. Пользуясь конфигуратором команд с официального сайта, составьте набор команд для установки последней версии Zabbix с поддержкой PostgreSQL и Apache.
4. Выполните все необходимые команды для установки Zabbix Server и Zabbix Web Server.

#### Требования к результатам 
1. Прикрепите в файл README.md скриншот авторизации в админке.
2. Приложите в файл README.md текст использованных команд в GitHub.
<img width="1364" height="639" alt="Снимок2" src="https://github.com/user-attachments/assets/95c6a6a3-1590-4ae6-9be2-184b25901b31" />

---

### Задание 2 

Установите Zabbix Agent на два хоста.

#### Процесс выполнения
1. Выполняя ДЗ, сверяйтесь с процессом отражённым в записи лекции.
2. Установите Zabbix Agent на 2 вирт.машины, одной из них может быть ваш Zabbix Server.
3. Добавьте Zabbix Server в список разрешенных серверов ваших Zabbix Agentов.
4. Добавьте Zabbix Agentов в раздел Configuration > Hosts вашего Zabbix Servera.
5. Проверьте, что в разделе Latest Data начали появляться данные с добавленных агентов.

#### Требования к результатам
1. Приложите в файл README.md скриншот раздела Configuration > Hosts, где видно, что агенты подключены к серверу
2. Приложите в файл README.md скриншот лога zabbix agent, где видно, что он работает с сервером
3. Приложите в файл README.md скриншот раздела Monitoring > Latest data для обоих хостов, где видны поступающие от агентов данные.
4. Приложите в файл README.md текст использованных команд в GitHub
<img width="1275" height="612" alt="забикс" src="https://github.com/user-attachments/assets/0145f6b5-ff72-4625-b780-1ca29a0b6a78" />
<img width="1366" height="673" alt="забикс1" src="https://github.com/user-attachments/assets/57ec362b-8fbb-4efb-aad6-192800758708" />
<img width="712" height="610" alt="zabbix-2" src="https://github.com/user-attachments/assets/e902dfd4-2dd6-41a6-854a-461675f73feb" />
<img width="1359" height="687" alt="zabix-2" src="https://github.com/user-attachments/assets/337a0e1e-f448-434a-ae7e-38738155a2af" />

---
