# module-1
This is project for module 1

pull request https://github.com/Ecool88/middle.messenger.praktikum.yandex/pull/18




Если не открыт pull request(вопрос уже задал как его открыть) можете чекнуть плиз по этой ссылке проект, там его копия https://github.com/Ecool88/module-1. Или подскажи плиз, где это сделать?  (вроде бы запушил все на ветку dev репозитория middle.messenger.praktikum.yandex, затем сделал pull request из dev в main тесты прошли, замерджил и появилась надпись "Pull request successfully merged and closed". Но ревьюер написал чтобы я открыл pull request)

Хотя вроде бы что-то пощелкал и вроде как создал pull request https://github.com/Ecool88/middle.messenger.praktikum.yandex/pull/20 вроде он открыт(сообщите на ревью как и что нужно было сделать)

команда npm run start собирает проект для режима разработки на 3000 порту с помощью parcel

Домен netify https://quizzical-kare-014a12.netlify.app/

Проект не готов к использованию т.к это первая итерация на ревью, хочу узнать ваше мнение комментарии по структуре проекта павильно ли реализована она? Накидал пока что 4 страницы с изначальной версткой.

Хотелось бы также узнать как вызвать функцию в .pug т.е сделать обработчик onClick, к примеру вы можете перейти в src/components/button/button.pug на кнопке button есть onclick='btnClick', функция btnClick написана src/components/button/button.js сам этот файл подключается а вот функция которая лежит в ней почему-то не находится, пробовал также вставить из DOM тоже не выходит, мб у вас будут какие-то ссылки на обработку кнопок или комментарии буду благодарен.

Вопрос по навигации тоже не пойму сейчас при запуске проекта страницы находятся по таким урл
    http://localhost:3000/profile/profile.html  profile
    http://localhost:3000/chats/chats.html      chats
    http://localhost:3000/login/login.html      login
    http://localhost:3000/signin/signin.html    signin

как сделать так чтобы навигация была к примеру http://localhost:3000/profile.html, я понимаю что это зависит от содержимого папки dist т.к там файлы .html вложены в папки, как от этого избавиться, я думаю что это из-за настройки сборки в parcel, также буду благодарен за ваши рекомендации

Вопрос насчет семантических тегов nav, header, main, footer они должны применяться на всех страницах? Можете для примера привести где будет актуально их применение?

По макету проекта оставил практические без изменений https://www.figma.com/file/a66YiMEpT1FZrLTxS9KjP0/Chat-Changed-fonts-colors изменил некоторые цвета

Вопрос по тз что значит "Разбейте все страницы на утилиты и модули"?

Хочу наследовать общие стили из src/layout/colors.scss но когда я подключаю через @import "src/layout/colors.scss" их почему-то не находит можете посмотреть в чем проблема в src/components/label-form/label-form.scss я оставил комментарий на первой строке можете посмотреть какая проблема с подключением может чего-то не хватает?




