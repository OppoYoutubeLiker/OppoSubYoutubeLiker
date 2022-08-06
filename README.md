<div align="center">
    <img height="150" src="https://raw.githubusercontent.com/OppoYoutubeLiker/OppoSubYoutubeLiker/main/Images/logo_small.png"></img>
    <h1>OppoSubYoutubeLiker(Скрипт пока не опубликован)</h1>
<h3>Это скрипт, который автоматически ставит лайк всем оппозиционным видео на которые вы подписаны на Youtube.</h3>
</div>

<br />

## Установка


 1) Установите в браузер дополнение для управления скриптами. Мы рекомендуем дополнение Tampermonkey, поскольку скрипт был написан в нем.

<div align="center">
  
   | [![Chrome](https://raw.githubusercontent.com/OppoYoutubeLiker/OppoYoutubeLiker/main/Images/chrome.png)](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)  | [![Firefox](https://raw.githubusercontent.com/OppoYoutubeLiker/OppoYoutubeLiker/main/Images/firefox.png)](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/) | [![Opera](https://raw.githubusercontent.com/OppoYoutubeLiker/OppoYoutubeLiker/main/Images/opera.png)](https://addons.opera.com/en/extensions/details/tampermonkey-beta/) | [![Safari](https://raw.githubusercontent.com/OppoYoutubeLiker/OppoYoutubeLiker/main/Images/safari.png)](https://apps.apple.com/us/app/userscripts/id1463298887)  | [![Edge](https://raw.githubusercontent.com/OppoYoutubeLiker/OppoYoutubeLiker/main/Images/edge.png)](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)  |
   | ------------- | ------------- | ------------- | ------------- | ------------- |
   | [Видеоинструкция](https://www.youtube.com/watch?v=cu4XeYtqXbM)  | [Видеоинструкция](https://www.youtube.com/watch?v=J9cbNOO2rew)  | [Видеоинструкция](https://www.youtube.com/watch?v=V090xyUf8dU)  | [Видеоинструкция](https://www.youtube.com/watch?v=iTyLQRVtMCA)  | [Видеоинструкция](https://www.youtube.com/watch?v=Bcs4HhQXCaU)  |

Альтернативные менеджеры скриптов: Violentmonkey или Greasemonkey

</div>
    
2) Нажмите на ссылку и установите скрипт: [![Install](https://raw.githubusercontent.com/OppoYoutubeLiker/OppoYoutubeLiker/main/Images/Install.png)](https://Link)

## Как это работает?
Как только пользователь попадает на страницу YouTube, скрипт каждые 10 секунд ( опционально) проверяет, просматривается ли видео канала, на который вы подписаны, и было ли оно уже лайкнуто. 

 - Кнопка "Вы подписаны" не имеет маркера, поэтому статус распознается при помощью поиска надписи на ней. Если надпись есть, то подписка оформлена, иначе - нет. Каждая надпись на всех языках находятся в массиве. Проще говоря, заключаются в квадратные скобки и кавычки.

```bash

 ["Вы подписаны", "Ви підписані", "Вы падпісаны", ... ]

```

 - Статус кнопки лайк считывается с маркера YouTube. Если лайк не поставлен, веб-страница с видео содержит маркер "false", в противном случае - "true".

API Youtube не требуется!

## Лицензия
Проект полностью с открытым исходным кодом. Наша собственная лицензия запрещает автократичным, диктаторским или ненавидящим демократию лицам использовать этот скрипт.

<div align="center">
  
[![GPLv3 License](https://raw.githubusercontent.com/OppoYoutubeLiker/OppoYoutubeLiker/main/Images/GPLv3.png)](https://opensource.org/licenses/)   [![OWN License](https://raw.githubusercontent.com/OppoYoutubeLiker/OppoYoutubeLiker/main/Images/OWN.png)]()
  
</div>


## Конфиденциальность
Этот скрипт уважает вашу конфиденциальность и не собирает никакой информации.
