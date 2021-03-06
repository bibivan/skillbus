# skillbus - система управления контактными данными.

![](https://i.ibb.co/M271MjL/skillbus.gif)

# Как запустить приложение?
Для работы с приложением, сначала необходимо запустить его серверную часть.
Перед запуском убедитесь, что вы установили Node.js версии 12 или выше.

Для запуска сервера перейдите в папку с репозиторием в подпапку crm-beckend и выполните в терминале команду node index.
Для остановки нажмите сочетание клавиш CTRL+C.

Далее перейдите в подпапку src и запустите файл index.html.

# Описание приложения
skillbus - это таблица со списком клиентов, содержащая 6 столбцов, в которых отображаются личные и контактные данные этих самых клиентов.

# Функционал
Сортировка. На все заголовки колонок, кроме контактов и действий, можно нажать, чтобы установить сортировку по соответствующему полю. Первое нажатие устанавливает сортировку по возрастанию, повторное - по убыванию.
Поиск. В поисковое строке вы можете ввести имя интересующего вас клиента. Если его данные есть в базе, то ссылка на них повяится во всплывающей подсказке под поиском, нажав на которую вы перейдете к соответствующей строке таблицы.
Действия. Доступно добавление, удаление, изменения данных пользователя. По нажатию на соответсвующие кнопки высплывает модальное окно, в котором можно работать с данными клиента.
