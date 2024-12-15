# Задание 1

**1. Проектирование**
Выбран фреймворк Webpack Module Federation, потому как наиболее прост в использовании и соответствует цели нашего задания: объединить все части сайта на основе единой технологии.

**2. Планирование изменений**

 - host, основное приложение :8080
 - auth, авторизация пользовтеля :8081
 - profile, профиль пользовтаеля :8082
 - card, картинка :8083
  
**./host/src/components**
 - Footer.js, подвал страницы
 - Header.js, заголовок страницы
 - InfoTooltip, информационное окно
 - Main.js, главный  
 - PopupWithForm, диалоговое окно 
 - ProtectedRoute.js, маршрутизация

**./auth/scr/components**
 - Login.js, авторизация пользователя 
 - Register.js, регистрация пользователя
	
**./profile/scr/components**
 - EditAvatarPopup, редактирования аватарки пользователя 
 - EditProfilePopup, редактирования профиля пользователя 
 - PopupWithForm, сохранениt пользователя

**./card/src/components**
 - AddPlacePopup, добавить картинку 
 - Card, карточка картинки 
 - ImagePopup, отображение картинки 
 - PopupWithForm, сохранение картинки
	
	
#  Задание 2

Файл draw.io по ссылке [arch_task_2.drawio](https://github.com/gen-arh-git/sprint_1/blob/main/arch_task_2.drawio)
