# General Information (Общие сведения)

### Определения базовых понятий:

## Топология:
Граф(схема) соединения компьютеров в сети

## Топология сети:
Конфигурация графа, где вершины - узлы сети(компьютеры и сетевое оборудование), а ребра - связи между узлами

## Сервис уровня: 
Описание того, какие функции реализует уровень. (что делает уровень)

## Протокол уровня:
Правила и соглашения, используемые для связи уровня-N с уровнем-N другого компьютера. (как уровень это делает)

## Интерфейс уровня: 
Набор примитивных операций, которые нижний уровень представляет верхнему уровню. (как получить доступ к сервису уровня)

## Модель OSI:

### 7 уровней модели:

Физический, канальный, сетевой, транспортный, сеансовый, представления, прикладной

#### Физический уровень:

Передача битов по каналу связи, не вникает в смысл передаваемой информации

#### Задача физического уровня:

Представление битов информации в виде сигналов, передаваемых по среде

#### Канальный уровень:

Передача сообщений по каналу связи

#### Задачи канального уровня:

Определение начала / конца сообщения в потоке бит, обнаружение и коррекция ошибок, управление доступом к среде передачи данных, физическая адресация

#### Сетевой уровень:

Объединяет сети построенные на основе разных технологий

#### Задачи сетевого уровня:

Создание составной сети, адресация(сетевые или глобальные адреса), определение маршрута пересылки пакетов в составной сети(маршрутизация)

#### Транспортный уровень:

Обеспечивает передачу данных между процессами на хостах

#### Задачи транспортного уровня:

Доставка данных с гарантией доставки(медленный вариант), быстрая доставка небольших наборов данных(быстрый вариант)

#### Сеансовый уровень:

Позволяет устанавливать сеанс связи

#### Задачи сеансового уровня:

Очередность передачи сообщений(управление), предотвращение одновременного выполнения критичной операции(управление маркерами), установка меток в сообщениях для возобновления передачи в случае сбоя(синхронизация)

#### Уровень представления и его задачи:

Обеспечивает согласование синтаксиса и семантики передаваемых данных(форматы представления чисел, форматы чисел), Шифрование и дешифрование(TLS / SSL) 

#### Прикладной уровень:

Набор приложений полезных пользователю

### Витая пара:
Вид кабеля связи. Представляет собой одну или несколько пар изолированных проводников, скрученных между собой (с небольшим числом витков на единицу длины), покрытых пластиковой оболочкой.

### Оптоволокно:
Нить из оптически прозрачного материала (стекло, пластик), используемая для переноса света внутри себя посредством полного внутреннего отражения.

### Коаксиальный кабель:
Электрический кабель, состоящий из центрального проводника и экрана, расположенных соосно и разделённых изоляционным материалом или воздушным промежутком

### Бит:
Единица измерения количества информации

### Кадр - фрейм:
Фрагмент данных протокола канального уровня модели OSI, передаваемый по линии связи

### Пакет:
Это определённым образом оформленный блок данных, передаваемый по сети в пакетном режиме

### Сегмент:
Любые данные транспортного уровня, принадлежащие протоколу TCP

### Дейтаграмма:
Блок информации, передаваемый протоколом через сеть связи без предварительного установления соединения и создания виртуального канала. Любой протокол, не устанавливающий предварительное соединение (а также обычно не контролирующий порядок приёма-передачи и дублирование пакетов), называется дейтограммным протоколом

### Концентратор - хаб:
Класс устройств для объединения компьютеров в сетях Ethernet с применением кабельной инфраструктуры типа витая пара

### Коммутатор - свитч:
Устройство, предназначенное для соединения нескольких узлов компьютерной сети в пределах одного или нескольких сегментов сети

### Маршрутизатор:
Специализированное устройство, которое пересылает пакеты между различными сегментами сети на основе правил и таблиц маршрутизации

### Модель TCP/IP:
*В процессе*

### Пропускная способность:
Это максимально допустимая скорость обработки трафика, которая определяется стандартами сети. Она показывает, какой максимальный объем может быть передан в единицу времени (чаще всего это одна секунда)

### MAC - адреса:
MAC - Управление доступом к среде

MAC-адреса используются для идентификации сетевых интерфейсов узлов сети

### LLC:
LLC - Верхний подуровень управления логической связью

Верхний подуровень канального уровня модели OSI, осуществляет: управление передачей данных; обеспечивает проверку и правильность передачи информации по соединению

### Ethernet:
Семейство технологий пакетной передачи данных между устройствами для компьютерных и промышленных сетей

### Классический Ethernet:
Компьютеры подключаются к концентратору с помощью витых пар, но внутри – общая шина, то есть все данные, которые приходят на один порт, передаются на все остальные порты. Для идентификации сетевых интерфейсов узлов внутри сети Ethernet используются MAC-адреса

### Коммутируемый Ethernet:
Суть коммутируемого Ethernet в том, что вместо хаба используется свитч (коммутатор) – устройство, которое работает на канальном уровне и обладает полносвязной топологией, что обеспечивает соединение всех портов друг с другом напрямую по технологии точка-точка

### Wi-Fi:
Технология беспроводной локальной сети

### Коллизия:
Наложение двух и более кадров от станций, пытающихся передать кадр в один и тот же момент времени в среде передачи коллективного доступа

### CSMA/CD:
Множественный доступ с прослушиванием несущей частоты и обнаружением коллизий

### CSMA/CA:
Множественный доступ с прослушиванием несущей частоты и исправлением коллизий

### DSL:
Цифровая абонентская линия

### Сетевой мост:
Предназначен для объединения сегментов (подсетей) компьютерной сети в единую сеть

### Порт:
Адрес транспортного уровня для определения какому приложению принадлежит сегмент

### VLAN:
Виртуальная локальная компьютерная сеть

### Протокол STP:
Протокол связующего(остовного) дерева. Автоматически отключает дублирующие соединения

### Протокол RSTP:
Быстрый протокол основного дерева

### Разделяемая среда:
Разделяемая среда — это такой способ организации работы сети, при котором сообщение от одной рабочей станции достигает всех других при помощи одного общего канала связи

### SSID:
Это символьное название беспроводной точки доступа Wi-Fi, служащее для идентификации её среди других точек пользователями или устройствами, подключающимися к сети

### BSSID:
Уникальный MAC-адрес беспроводной сети

### MTU:
Максимальная единица передачи

### Хост:
Любое устройство, предоставляющее сервисы формата «клиент-сервер» в режиме сервера по каким-либо интерфейсам и уникально определённое на этих интерфейсах. В более широком смысле под хостом могут понимать любой компьютер, подключённый к локальной или глобальной сети

### Маршрутизация - routing:
Процесс поиска маршрута доставки пакета между сетями через транзитные узлы - маршрутизаторы

### Продвижение - forwarding:
Процесс передачи пакета внутри маршрутизатора в соответствии с правилами маршрутизации

### IP-адрес:
Глобальный адрес сетевого уровня, используемый в стеке протоколов TCP / IP и Интернет

### Протокол IP:
Межсетевой протокол(протокол межсетевого взаимодействия), целью которого является объединить сети построенные с помощью разных технологий канального уровня

### ICMP:
Протокол межсетевых управляющих сообщений(сообщения об ошибках в сети, тестирование работы сети)

### ARP:
Протокол разрешения адресов(позволяет определить по IP-адресу компьютера его MAC-адрес)

### DHCP:
Протокол динамической конфигурации хостов(позволяет назначить компьютерам в сети IP-адрес) и другой конфигурационной информации

### Подсеть - subnet:
Множество компьютеров, у которых старшая часть IP-адреса одинаковая

### Маска подсети:
Показывает, где в IP-адресе номер сети, а где номер хоста

### Типы IP-адресов:

1. Внутренний (он же частный, локальный, “серый”) IP
2. Внешний (он же публичный, глобальный, “белый”) IP
3. Статический IP
4. Динамический IP

### ICANN:
Корпорация по управлению доменными именами и IP-адресами

### NAT:
Технология преобразования IP-адресов внутренней(частной) сети в IP-адреса внешней сети(Интернет) - (Трансляция сетевых адресов) 

### internetworking:
Объединение сетей

### internet:
Объединенная сеть

### Internet:
Название самой крупной объединенной сети

### TTL:
Предельный период времени или число итераций, или переходов, которые набор данных (пакет) может осуществить (прожить) до своего исчезновения

### Шлюз - gateway - default router:
Маршрутизатор, на который отправляются пакеты для неизвестных сетей

### Фрагментация:
Разделение пакета на несколько частей(фрагментов) для передачи по сети с маленьким MTU

### Идентификатор Пакета:
Задает номер пакета, который разбит на фрагменты

### Смещение Фрагмента:
Смещение фрагмента в поле данных исходного пакета

### SSH:
SSH означает Secure Shell и является протоколом для безопасного входа в удаленные системы. Это наиболее распространенный и простой способ доступа к удаленным серверам на базе Linux. Для этого вам необходимо знать имя домена и IP-адрес

### TELNET:
SSH – это в сетевой протокол, который используется для удаленного доступа и управления любым устройством. Основное различие между SSH и Telnet состоит в том, что SSH использует шифрование, что означает, что все данные, передаваемые по сети, защищены от отслеживания. Telnet все же не так безопасен. Как и Telnet, пользователь, который хочет получить доступ к удаленному устройству, должен установить SSH-клиент

### Кэш*:
Промежуточный буфер с быстрым доступом к нему, содержащий информацию, которая может быть запрошена с наибольшей вероятностью. Доступ к данным в кэше осуществляется быстрее, чем выборка исходных данных из более медленной памяти или удалённого источника, однако её объём существенно ограничен по сравнению с хранилищем исходных данных

### Буфер*:
Это область памяти, используемая для временного хранения данных при вводе или выводе. Обмен данными (ввод и вывод) может происходить как с внешними устройствами, так и с процессами в пределах компьютера. Буфера могут быть реализованы в аппаратном или программном обеспечении, но подавляющее большинство буферов реализуется в программном обеспечении. Буфера используются, когда существует разница между скоростью получения данных и скоростью их обработки или в случае, когда эти скорости переменны, например, при буферизации печати

### Web-Сервер:
Сервер, принимающий HTTP-запросы от клиентов, обычно веб-браузеров, и выдающий им HTTP-ответы, как правило, вместе с HTML-страницей, изображением, файлом, медиа-потоком или другими данными

### TCP:
Протокол управления передачей. Предназначен для управления передачей данных интернета. Пакеты в TCP называются сегментами

### UDP:
Протокол пользовательских датаграмм

### Сокет:
Сокет — это виртуальная конструкция из IP-адреса и номера порта. Её придумали для того, чтобы разработчикам было проще писать код, а программы могли передавать данные друг другу даже в пределах одного компьютера (де-факто стандарт интерфейсов для транспортной подсистемы)ТФ

### Компьютерная сеть:
Система, обеспечивающая обмен данными между вычислительными устройствами — компьютерами, серверами, маршрутизаторами и другим оборудованием или программным обеспечением

### DNS:
Система доменных имен позволяет преобразовать имена компьютеров в IP-адреса

### Размер окна:
Количество байтов данных, которые могут быть переданы без получения подтверждения

### Управление потоком:
Предотвращение "затопления" медленного получателя быстрым отправителем

### Окно управления потоком:
Размер задается получателем в зависимости от места в буфере

### Окно перегрузки:
На стороне отправителя, его размер рассчитывается отправителем в зависимости от нагрузки сети, и от того сколько данных может принять приложение

### AIMD:
Аддиктивное увеличение / Мультипликативное уменьшение

### Управление перегрузкой:
Предотвращение отправки в сеть большого количества сегментов, которые перегрузят сетьС

### Внешние IP-адреса:
Это уникальный адрес, под которым компьютер виден прочим устройствам в глобальной сети. Доступ к устройству с внешним адресом осуществим из любой точки всемирной паутины

### Внутренние IP-адреса:
Такие адреса предназначены для применения в локальных сетях, распределение таких адресов никем не контролируется. В связи с дефицитом свободных IP-адресов провайдеры всё чаще раздают своим абонентам именно внутрисетевые адреса, а не внешние, при этом они все выходят в интернет через один внешний IP (так называемый «белый IP»)

### Межсетевой экран - firewall - брандмауэр:
Отделяет сеть от других сетей

### Content-filter:
Устройство или программное обеспечение для фильтрации сайтов по их содержимому, не позволяющее получить доступ к определённым сайтам или услугам сети Интернет

### HTTP:
Протокол передачи гипертекста

### HTTPS:
Защищенный протокол передачи гипертекста

### SMTP:
Простой протокол передачи почты

### POP3:
Протокол почтового отделения(устарел)

### IMAP:
Протокол доступа к электронной почте

### FTP:
Протокол передачи данных

### Сеанс(сессия):
Набор связанный между собой сетевых взаимодействий, направленных на решение одной задачи

### Token:
Метка

### TSL/SSL:
*В процессе изучения*

### Домен:
Домен — это имя сайт

### CNAME:
Определяет псевдоним для другого доменного имени

### URL:
Уникальное положение ресурса

### Прокси-сервер:
Промежуточный сервер (комплекс программ) в компьютерных сетях, выполняющий роль посредника между пользователем и целевым сервером (при этом о посредничестве могут как знать, так и не знать обе стороны), позволяющий клиентам как выполнять косвенные запросы (принимая и передавая их через прокси-сервер) к другим сетевым службам, так и получать ответы. Сначала клиент подключается к прокси-серверу и запрашивает какой-либо ресурс (например e-mail), расположенный на другом сервере. Затем прокси-сервер либо подключается к указанному серверу и получает ресурс у него, либо возвращает ресурс из собственного кэша (в случаях, если прокси имеет свой кэш). В некоторых случаях запрос клиента или ответ сервера может быть изменён прокси-сервером в определённых целях. Прокси-сервер позволяет защищать компьютер клиента от некоторых сетевых атак и помогает сохранять анонимность клиента, но также может использоваться мошенниками для скрытия адреса сайта, уличённого в мошенничестве, изменения содержимого целевого сайта (подмена), а также перехвата запросов самого пользователя

### Обратный прокси:
Тип прокси-сервера, который ретранслирует запросы клиентов из внешней сети на один или несколько серверов, логически расположенных во внутренней сети. При этом для клиента это выглядит так, будто запрашиваемые ресурсы находятся непосредственно на прокси-сервере.[1] В отличие от классического прокси, который перенаправляет запросы клиентов к любым серверам в Интернете и возвращает им результат, обратный прокси непосредственно взаимодействует лишь с ассоциированными с ним серверами и возвращает ответ только от них

### Протокол:
Протокол - это согласованный способ форматирования данных, чтобы два или более устройств могли взаимодействовать друг с другом и понимать друг друга

### Ethernet и Wi-Fi: 
Ethernet - это протокол для физических сетевых подключений, который требует использования кабелей Ethernet. WiFi - это протокол для подключения к сети через радиоволны

### Интернет-протокол (IP):
Это протокол или набор правил для маршрутизации и адресации пакетов данных, чтобы они могли перемещаться по сетям и прибывать в нужное место назначения

### Протокол(еще раз):
В сети протокол - это стандартизированный способ выполнения определенных действий и форматирования данных таким образом, чтобы два или более устройств могли взаимодействовать друг с другом и понимать друг друга

### Ethernet:
Это протокол уровня 2 для отправки данных между устройствами. В отличие от Wi-Fi, Ethernet требует физического подключения через кабель Ethernet

### Сеть:
Это группа подключенных компьютеров, которые могут отправлять данные друг другу

### Контейнеризация (виртуализация на уровне ОС):
Технология, которая позволяет запускать программное обеспечение в изолированных на уровне операционной системы пространствах

### Виртуализация:
Это сокрытие конкретной реализации за универсальным стандартизованным методом обращения к ресурсам. Иными словами, это создание абстракции над аппаратным обеспечением

### Аппаратная абстракция
Это наборы процедур в программном обеспечении, которые предоставляют программам доступ к аппаратному обеспечению ресурсы через программные интерфейсы

### Гипервизор:
Обеспечивает изолированную среду выполнения для каждой виртуальной машины, а также управляет доступом ВМ и гостевых ОС к аппаратным ресурсам

Говоря простыми словами, гипервизор обеспечивает параллельное и независимое функционирование нескольких операционных систем на одном компьютере

### Docker: 
Это платформа контейнеризации с открытым исходным кодом, с помощью которой можно автоматизировать создание приложений, их доставку и управление

### Dockerfile
Это конфигурационный файл, в котором описаны инструкции, которые будут применены при сборке Docker-образа и запуске контейнера