<h1>Дипломный проект по профессии "QA Engineer"</h1>
<h2>Запуск автотестов</h2>
<details><summary>Предусловия</summary>
    <ul>
        <li>Установлена Android Studio</li>
        <li>Установлена последняя стабильная версия Android SDK</li>
        <li>Android эмулятор с API 29, с русским языком системы</li>
        <li>Установлен Allure</li>
    </ul>
</details>

<ol>
    <li>Склонировать репозиторий с проектом
        <a href="https://github.com/gulyolik/DiplomaProject.git">gulyolik/DiplomaProject</a>.
    </li>
    <li>Открыть репозиторий в AndroidStudio.</li>
    <li>Переопределить JAVA используемую в проекте на JAVA_HOME.</li>
    <li>Скомпилировать проект.</li>
    <li>Запустить Android эмулятор/телефон с API 29.</li>
    <li>Запустить выполнение тестов командной "./gradlew connectedAndroidTest" из терминала AndroidStudio.</li>
    <li>По окончании прогона автотестов, выгрузить папку "allure-results". По пути "Device Explorer/sdcard/googletests/test_outputfiles/allure-results"</li>
    <li>В папке, находящейся выше уровнем, чем allure-results, запустить команду "allure serve" для того, чтобы получить визуализацию результатов тестов в виде index.html</li>
</ol>
