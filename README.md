# **МИНИСТЕРСТВО ОБРАЗОВАНИЯ И НАУКИ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ АВТОНОМНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ»**
Факультет <ins>физико-математических и естественных наук.</ins>  
Кафедра <ins>информационных технологий</ins>  
## Отчет по лабораторной работе
Тема "Основы интерфейса с взаимодействия пользователя с системой Unix на уровне командной строки" по дисциплине "Операционные системы"  
Выполнил:  
Студент группы <ins>НПИбд-02-21</ins>  
<ins>М Шaриф Камран</ins>  
<ins>"30" апреля 2022г.</ins>  
Москва 2022  
- **Цель работы:**
 - Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки
- **Ход работы:**
 - Заходим в терминал в системе Linux.
 - Далее заходим в каталог tmp и смотрим его содержимое
<img width="646" alt="image" src="https://user-images.githubusercontent.com/103488170/166118491-1f4f1f21-5b18-4100-b62e-6a4792e9282b.png">

 - Затем переходим в каталог /var/spool и проверяем при помощи команды ls содержимое данного каталога. Проверяем есть ли в нем каталог cron. Его там не оказалось
<img width="564" alt="image" src="https://user-images.githubusercontent.com/103488170/166118756-908c04d4-8cd0-4824-969e-7c8cf98fd3b3.png">


 - Далее переходим в домашний каталог и проверяем, кому принадлежат файлы при помощи ls -l
<img width="582" alt="image" src="https://user-images.githubusercontent.com/103488170/166118534-bc193e5f-446b-4233-a4cf-3e918e3ee678.png">

 - Затем создаем новый каталог newdir, переходим в него и создаем каталог morefun.
<img width="897" alt="image" src="https://user-images.githubusercontent.com/103488170/166118812-137c90cb-04ab-4b6b-bc98-7cb148c9ce85.png">

 - Далее создаем три каталога "letters", "memos" и "misk" одной командой "mkdir *имя_каталога* *имя_каталога* *имя каталога*"
<img width="489" alt="image" src="https://user-images.githubusercontent.com/103488170/166118939-709d914f-c62d-487d-a2ac-a4b0bd078145.png">

 - Далее пытаемся удалить все три каталога одной командой "rm", однако система не удаляет их.
<img width="563" alt="image" src="https://user-images.githubusercontent.com/103488170/166118931-0506573b-83ae-4bac-8ee2-c0074ec51dca.png">

 - Далее проверим при помощи какой команды можно посмотреть не только содержимое каталога, но и его подкаталогов. Для этого введем команду "man ls".
<img width="574" alt="image" src="https://user-images.githubusercontent.com/103488170/166118957-e7ea88d9-9012-4988-93d5-07b8dface671.png">

 - Выясним, что делать это можно при помощи команды "ls -a"
 - <img width="570" alt="image" src="https://user-images.githubusercontent.com/103488170/166118985-f46440f7-d1e4-4aa8-8ae4-286114b3e2aa.png">

 - Далее поработаем с командой "history' - она позволяет увидеть историю введенных нами команд
<img width="380" alt="image" src="https://user-images.githubusercontent.com/103488170/166119000-d284ca23-443d-45cf-b501-f2a6f520e2ec.png">


 - Можно скопировать любуй из этих команд и воспользоваться еще раз, или проще можно нажимать клавишу "стрелка вверх" и в строке будут появляться команды, использованные ранее
<img width="565" alt="image" src="https://user-images.githubusercontent.com/103488170/166119015-252c4071-f9eb-4107-882c-9d98f44c67b5.png">

Ответы на контрольные вопросы:

1). Компьютерный терминал — устройство ввода–вывода, основные функции которого заключаются в вводе и отображении данных. У компьютерного терминала есть преимущества перед графическим интерфейсом: — снижение начальных затрат на приобретение персональных компьютеров, поскольку требования к их конфигурации минимальны, а тонкие клиенты производятся без встроенных носителей информации. — унификация – все терминалы имеют одинаковый набор программного обеспечения. — простота первоначального внедрения – нет необходимости настраивать каждый персональный компьютер в отдельности, присутствует централизованное управление информационным процессом. — экономия времени системного администратора. Все тонкие клиенты абсолютно одинаковы, вероятность поломок сведена к минимуму, а программное обеспечение установлено только на сервере. — масштабируемость. Созданный единожды образ системы для работы всей группы пользователей позволяет при минимальных затратах поддерживать легко масштабируемую сеть. Возможно быстрое создание любого количества новых рабочих мест. — безопасность и отказоустойчивость. Компьютерный терминал, загружаясь, получает операционную систему «от производителя», настройка которой осуществляется только отделом информационной поддержки. Все модификации операционной системы и прикладных программ никак не влияют ни на других пользователей, ни на образ, хранящийся на сервере. Вся пользовательская информация хранится на сервере и регулярно резервируется, что увеличивает отказоустойчивость. — защита от утечек информации – нет локальных носителей – нет возможности делать копии документов на съемные носители информации.

2). Входное имя пользователя (Login) —название учётной записи пользователя. Входному имени пользователя ставится в соответствиевнутренний идентификатор пользователя в системе (User ID,UID) — положительное целое число в диапазоне от 0 до65535, по которому в системе однозначно отслеживаются действия пользователя.

3). Учётные записи пользователей хранятся в файле/etc/passwd,который имеет следу-ющую структуру:login:password:UID:GID:GECOS:home:shell . Например,учётные записи пользователейrootиivanв файле/etc/passwdмогутбыть записаны следующим образом:root❌0:0:root:/root:/bin/bashivan❌1000💯:/home/ivan:/bin/bash .

4). Начиная с версии 4.6, настройки рабочей среды хранятсяв реестреx fconf.

5). В многопользовательской модели пользователи делятся напользователей с обычными правамии администраторов. Входному имени пользователя ставится в соответствие внутренний идентификатор пользователя в системе (User ID,UID) — положительное целое число в диапазоне от 0 до 65535, по которому в системе однозначно отслеживаются действия пользователя.

6). Полномочия пользователей с административными правами обычно не ограничены. В многопользовательской модели пользователи делятся напользователей с обычными правамии администраторов. Пользователь с обычными правами может производить действия с элементами операционной системы только в рамках выделенного ему пространства и ресурсов, не влияя на жизнеспособность самой операционной системыи работу других пользователей.

7). Процедура регистрации в системе обязательна для Linux. Каждый пользователь операционный системы имеет определенные ограничения на возможные с его стороны действия: чтение, изменение, запуск файлов,а так же на ресурсы: пространствона файловой системе, процессорное время для выполнение текущих задач (процессов).При этом действия одного пользователя не влияютна работу другого.Такая модель разграничения доступа к ресурсам операционной системы получила название многопользовательской.

8). Учётная запись пользователя содержит: –входное имя пользователя (Login Name); –пароль (Password); –внутренний идентификатор пользователя (User ID); –идентификатор группы (Group ID); –анкетные данные пользователя (General Information); -домашний каталог (Home Dir); –указатель на программную оболочку (Shell).

9). Входному имени пользователя ставится в соответствиевнутренний идентификатор пользователя в системе (User ID,UID) — положительное целое число в диапазоне от 0 до65535, по которому в системе однозначно отслеживаются действия пользователя. Пользователю можетбыть назначена определенная группа для доступа к некоторымресурсам, разграничения прав доступа к различным файлам и директориям. Каждаягруппа пользователей в операционной системе имеетсвой идентификатор—Group ID(GID).

10). Анкетные данные пользователя (General Information или GECOS) являются необязательным параметром учётной записи и могут содержать реальное имя пользователя (фамилию,имя),адрес,телефон.

11). Для каждого пользователя организуется домашний каталог, где хранятся его данныеи настройки рабочей среды. В домашнем каталоге пользователя хранятся данные (файлы) пользователя,настройки рабочего стола и других приложений. Содержимое домашнего каталога обычно недоступно другим пользователям с обычными правами и не влияет на работу и настройки рабочей среды других пользователей.

12). Мой домашний каталок: /afs/.dk.sci.pfu.edu.ru/home/t/b/tbkonovalova (узнаём с помощью команды pwd)

13). Администратор имеет возможность изменить содержимое домашнего каталогапользователя.

14). Учётные записи пользователей хранятся в файле/etc/passwd, который имеет следующую структуру: login:password:UID:GID:GECOS:home:shell

15). Для того, чтобы посмотреть содержимое файла /etc/shadow : изначально поле пароля содержало хеш пароля и использовалось для аутентификации.Однако из соображений безопасности все пароли были перенесены в специальный файл /etc/shadow, недоступный для чтения обычным пользователям. Поэтому в файле /etc/passwdполеpassword имеет значение x. Символ* в поле password некоторой учётной записи в файле /etc/passwd означает, что пользователь не сможет войти в систему.

16). Виртуальные консоли — реализация концепции многотерминальной работы в рамках одного устройства. Мне кажется, что в данном контексте слово "виртуальный" означает реализованный программно, симулированный, имитированный с помощью компьютера.

17). Данная программа управляет доступом к физическим и виртуальным терминалам (tty).

18). Весь процесс взаимодействия пользователя с системой с момента ре-гистрации до выхода называетсясеансом работы.

19). Toolkit (Tk,«набор инструментов»,«инструментарий») — кроссплатформенная библиотека базовых элементов графического интерфейса, распространяемая с открытыми исходными текстами.

20). Используются следующие основныетулкиты: –GTK+ (сокращение от GIMP Toolkit) — кроссплатформенная библиотека элементов интерфейса; –Qt—кросс - платформенный инструментарий разработки программного обеспеченияна языке программирования C++. GTK+ состоит из двух компонентов: –GTK—содержит набор элементов пользовательского интерфейса (таких, как кнопка, список, поле для вводатекста ит.п.) для различных задач; –GDK — отвечает за вывод информации на экран, может использовать для этого X Window System, Linux Framebuffer, WinAPI.
### Вывод: я приобрел практические навыки взаимодействия пользователя с системой посредством командной строки.
