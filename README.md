<h1>Contact Service</h1>
<p>Проект представляет собой веб-приложение на Spring Web, позволяющий работать со списком контактов.</p>
<p>Сущность контакт состоит из следующий полей: Id, Имя, Фамилия, Email, Телефонный номер</p>
<p>Контакты хранятся в Postgres, по умолчанию, подключение происходит со следующими параметрами:</p>
<ui>
<li>DB_URL - jdbc:postgresql://localhost:5432/postgres</li>
<li>DB_USERNAME - postgres</li>
<li>DB_PASSWORD - postgres</li>
</ui>
<p>Но если у вашей бд другие параметры, то их можно переопределить через переменные среды</p>
<p>Основная страница доступна по http://localhost:8080/contacts. На этой странице отображаются все контакты, которые есть в базе.</p>
<p>Также на этой странице есть три ссылки:</p>
<ui>
<li>Создать - перебрасывает на форму создания контакта. После заполнения полей и нажатии Save, перебрасывает на главную страницу</li>
<li>Удалить - отображается напротив каждого контакта - удаляет контакт</li>
<li>Редактировать - перебрасывает на форму редактирования контакта. Выглядит также, как и форма сохранения, но уже с заполнеными полями. После нажатия Save перебрасывает на главную страницу и применяет изменения, внесенные в контакт</li>
</ui>

