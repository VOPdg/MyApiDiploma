#  Автоматизация тестирования API на сайте - reqres.in.
> <a target="_blank" href="https://reqres.in/">Ссылка на страницу сайта</a>

###  Содержание:

- [Технологии и инструменты](#techno-технологии-и-инструменты)
- [Запуск из терминала](#arrow_forward-запуск-из-терминала)
- [Сборка в Jenkins](#jenkins-Jenkins-job)
- [Allure отчет](#report-Allure-отчет)
- [Интеграция с Allure TestOps](#Allure-TestOPS)
- [Отчет в Telegram](#telegram-Уведомление-в-Telegram-при-помощи-бота)

<a name="techno-технологии-и-инструменты"></a>
## Технологии и инструменты:

<p align="center">
<img width="8%" title="IntelliJ IDEA" src="images/logo/Intelij_IDEA.svg">
<img width="8%" title="Java" src="images/logo/Java.svg">
<img width="8%" title="JUnit5" src="images/logo/JUnit5.svg">
<img width="8%" title="Selenide" src="images/logo/Selenide.svg">
<img width="8%" title="Gradle" src="images/logo/Gradle.svg">
<img width="8%" title="GitHub" src="images/logo/GitHub.svg">
<img width="8%" title="Jenkins" src="images/logo/Jenkins.svg">
<img width="8%" title="Allure Report" src="images/logo/Allure_Report.svg">
<img width="8%" title="Allure TestOps" src="images/logo/AllureTestOps.svg">
<img width="8%" title="Telegram" src="images/logo/Telegram.svg">
</p>

## :arrow_forward: Запуск из терминала
Локальный запуск:
```
gradle clean test
```
## :robot: Сборки в Jenkins
### <a target="_blank" href="https://jenkins.autotests.cloud/job/qa_guru_Jenkinsjob_MyApiDiploma/">Параметризированная сборка в Jenkins со всеми тестами</a>
<p align="center">
<img title="Jenkins Job Run with parameters" src="images/screenshots/Screenshot 2022-09-11 at 14.15.04.png">
</p>


## :bar_chart: Allure отчет
- ### Главный экран отчета
<p align="center">
<img title="Allure Overview Dashboard" src="images/screenshots/Screenshot 2022-09-11 at 14.17.52.png">
</p>

- ### Страница с проведенными тестами
<p align="center">
<img title="Allure Test Page" src="images/screenshots/Screenshot 2022-09-11 at 14.19.32.png">
</p>

<a name="Allure-TestOPS"></a>
### <img width="4%" title="Allure TestOPS" src="images/logo/AllureTestOps.svg"> Интеграция с [Allure TestOps](https://allure.autotests.cloud/launch/14588)
<p align="center">
  <img src="images/screenshots/Screenshot 2022-09-11 at 14.20.54.png" alt="job">
</p>

<p align="center">
  <img src="images/screenshots/Screenshot 2022-09-11 at 14.22.40.png" alt="job">
</p>

<a name="telegram-Уведомление-в-Telegram-при-помощи-бота"></a>
### <img width="6%" title="Jenkins" src="images/logo/Telegram.svg"> Отчет в Telegram

<p align="center">
  <img src="images/screenshots/Screenshot 2022-09-11 at 14.23.57.png" alt="job">
</p>