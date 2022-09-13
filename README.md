Краткое описание:
Небольшой проект отображающий работу с сестью. Загрузка, выгрузка картинок c сервера при помощи api.
Парсинг полученной информации от сервера в JSON, и соответствующее отображение. Отправка POST и GET запросов на сервер.

Основной стек технологий: 
UIKit, MVVM, URLSession, Alamofire, GCD, UserDefaults, Notifications, Storyboard. 

Основная информаиця о проекте: 
1. Проект написан полностью на UIKit.
2. Использовал паттерн архитектуры MVVM. 
3. В качестве сетевых запросов используется URLSessin и Alamofire. 
4. Продемонстированна работа с многопоточностью GCD
5. Работа с Notifications (оповещение об окончании загрузки в фоне)
6. В проект инмпортирован менеджер CocoaPods.
7. Написано небольшое количество простых Unit тестов.
8. Продемонстированна работа с Storyboard.
9. В проекте используется Navigation Controller.
10. В проекте используется TableView и CollectionVide 
11. Сохранения выбранного варианта работы сетью (URLSession/Alamofire) в локальное хранилище UserDefaults.

<img src="NetworkProject/Assets.xcassets/Example.dataset/Example.gif" width="300" height="650"/>