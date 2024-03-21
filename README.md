# Системные требования Windows 11

Основным объектом для критики в адрес **Windows 11** стали обновлённые системные требования, которые обескуражили многих пользователей ПК. Так, после презентации неожиданно выяснилось, что среди прочего для установки новой ОС в компьютере должен присутствовать криптографический модуль [*Trusted Platform Module (TPM) 2.0*](https://learn.microsoft.com/ru-ru/windows/security/hardware-security/tpm/trusted-platform-module-overview), а материнская плата должна обладать поддержкой UEFI и функцией безопасной загрузки системы Secure Boot. Подлил масла в огонь и опубликованный Microsoft список поддерживаемых процессоров, который оставил у разбитого корыта владельцев вычислительных машин с чипами старее AMD Ryzen второго поколения или восьмого поколения Intel Core. В компании объяснили «выбраковку» ~~устаревшего~~ оборудования стремлением обеспечить наилучшую безопасность платформы, а также совместимость с современными средствами шифрования и аутентификации.

Такое оправдание не нашло понимания в пользовательской среде, в результате чего Microsoft пришлось пойти на уступки и объявить о планах по пересмотру минимальных системных требований. Кроме того, компания пообещала выпустить специальные сборки Windows 11 для систем без TPM на отдельные рынки — в страны вроде России и Китая. Примечательно, что на фоне этих заявлений Microsoft временно удалила утилиту *PC Health Check*, которая позволяла проверить компьютер на совместимость с новой **Windows 11**. Всё это лишний раз свидетельствует о неразберихе, которая творится в кулуарах корпорации.

|Процессор |ОЗУ |Память |Системная прошивка  |TPM |Видеоадаптер |
|----|----|----|----|----|----|
|Не менее двух ядер с частотой не менее 1 ГГц|4 гигабайта|Устройство хранение на 64 и более ГБ|UEFI с поддержкой безопасной загрузки|TPM версии 2.0|Совместим с DirectX 12|

## Альтернативы Windows 11
Если новая **Windows 11** вас не устраивает, то в качестве альтернативы можно рассмотреть:
1. [Linux](https://ru.wikipedia.org/wiki/Linux)
2. [macOS](https://ru.wikipedia.org/wiki/MacOS)
3. [Windows 10](https://ru.wikipedia.org/wiki/Windows_10)
4. [Windows XP](https://ru.wikipedia.org/wiki/Windows_XP)[^1]

___
# Минутка полезной информации
Если у вас установлен Линукс и вы умеете открывать терминал, то с помощью следующих программ можно получить случайную цитату.
Установка пакета: ``sudo apt-get install fortune``
Установка русских цитат: ``sudo apt-get install fortunes fortune-mod fortunes-min fortunes-ru``
Сама команда: ``fortune -s``
___
# Цитата
> "Живи, кайфуй, гуляй, играй, упал вставай, наглей, ругай, чужих роняй, своих спасай, пельмени, суп, картошка чай."  © Джейсон Стэйтем
![Легенда](https://zhiznsovkusom.ru/wp-content/uploads/2022/02/38..jpg)

___
# Элементы, исполользованные в данной работе
- [ ] Заголовки
- [ ] Выделение
- [ ] Ссылки
- [ ] Полосы
- [ ] Цитаты
- [ ] Списки
- [ ] Таблицы
- [ ] Синтаксис кода
- [ ] Сноски
- [ ] Списки задач
- [ ] Изображения
- [ ] Содержание
---
# Содержание
- [Системные требования Windows 11](#Системные-требования-Windows-11)
	- [Альтернативы Windows 11](##Альтернативы-Windows-11)
- [Минутка полезной информации](#Минутка-полезной-информации)
- [Цитаты](#Цитаты)
- [Элементы, исполользованные в данной работе](#Элементы,-исполользованные-в-данной-работе)

[^1]: Шутка от автора. Огромная просьба не издеваться над собой и не пытаться поставить эту версию Windows на ваш компьютер. Берегите себя и своих близких.
