<h1>Мафия</h1>
Пользователи создают настраиваемое лобби:
<ul>
    <li>Название лобби</li>
    <li>Открытое/закрытое</li>
    <li>Пароль, если лобби закрытое</li>
</ul>
<br>
Игра начинается, когда лобби полностью заполненно. Игрокам случайным образом распределюются роли.
После завершения матча у всех игроков обновляется статистика побед.

<h2>ТЗ</h2>
<ul>
    <li>Создать БД с таблицами лобби пользователей и игроков(игрок-пользователь находящийся в определённом лобби)</li>
        <br>Лобби
        <ul>
            <li>id</li>
            <li>Название</li>
            <li>Открытое/закрытое</li>
            <li>Пароль, если лобби закрытое</li>
        </ul><br>
        Пользователи
        <ul>
            <li>id</li>
            <li>Логин</li>
            <li>Пароль</li>
            <li>Аватарка</li>
        </ul><br>
        Игроки
        <ul>
            <li>id</li>
            <li>Роль в игре</li>
            <li>Жив/мертв</li>
            <li>id пользователя</li>
            <li>id лобби</li>
        </ul>
    <li>Сделать стартовую страницу</li>
    <li>Сделать страницы авторизации и регистрации</li>
    <li>Сделать страницу для отборажения лобби</li>
    <li>Сделать страницу лобби</li>
    <li>Сделать страницу профиля пользователя</li>

</ul>
<h2>Пояснительная записка</h2>
<b>Автор</b>: Лодыгин Антон<br>

<b>Идея</b>: Сделать игру "Мафия" онлайн, используя Flask<br>

<b>Реализация</b>:

Созданы orm модели пользователей, лобби и игроков. Сверстанны страницы со списком лобби, стартовая, авторизации, регистрации, игрового лобби, профиля пользователя.
Было использованно много джаваскрипта, а мегасложная технология WebSocket.<br>
Библиотеки: flask, flask-login, flask-socketio, flask-wtf, sqlalchemy, werkzeug, wtforms, sqlalchemy-serializer, flask-restful
<h2>Презентация</h2>
https://docs.google.com/presentation/d/1YcznfBaLFPh57M0gDDZyJudMAoLUoquXeVaU0jFP63A/edit?usp=sharing