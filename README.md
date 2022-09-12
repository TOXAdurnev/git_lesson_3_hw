# Инструкция по работе с удалённым репозиториям

## Клонирование чужих репозиториев 
* На GitHub выбираем интересующий нас репозиторий 
* Нажимаем кнопку **Code**
* Копируем **HTTPS**-адрес
* Воодим команду в терминале 
```
git clone <скопированный HTTPS-адрес>
Пример:
https://github.com/TOXAdurnev/git_lesson_3_hw.git
```
![clone](https://github.com/TOXAdurnev/git_lesson_3_hw/blob/NewGuide/images/clone.PNG)



## Pull request 
* Находим интересующий нас проект для которого мы хотим предлождить изменения.
* Нажимаем кнопку **Fork**
![fork](https://github.com/TOXAdurnev/git_lesson_3_hw/blob/NewGuide/images/Fork.PNG)
* Вводим название как он у нас будет называться (Он появится на нашем аккаунте GitHub)
* Делаем клонирование на локальный репозиторий
* Создаем новую ветку
`ВАЖНО!!! Pull request делаем только в отдельной ветке. В основной ветке менять ничего не надо`

Команда для создания и перехода в новую ветку
```
git checout -b <имя новой ветки>
```
* После внесения изменений/предложений используем команду

```
git push -u oriigin <имя новой ветки>
```
* Переходим во вкладку Pull request
* Нажимаем ктопку New pull request

![pull_reauests](https://github.com/TOXAdurnev/git_lesson_3_hw/blob/NewGuide/images/pull_reaqests.PNG)

* Выбираем номую ветку 
* нажимаеv View pull request
![pull_reauests](https://github.com/TOXAdurnev/git_lesson_3_hw/blob/NewGuide/images/View_pull_request.PNG)
* И завершающий этам нажать кнопку Create pull request
