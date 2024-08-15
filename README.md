## Приветствие

Здравствуйте! Мы — [EK SoftWare](https://github.com/EK-SoftWare-RU), а также я, [ErkinKraft](https://github.com/ErkinKraft). Сегодня, 15 августа 2024 года, мы рады сообщить вам о внедрении новой меры безопасности для наших проектов.

## Подписание файлов с помощью GPG

С целью повышения доверия и безопасности, мы начали использовать GPG ключи для подписи наших файлов. Это означает, что теперь вы сможете легко проверить достоверность загружаемых вами файлов и убедиться в том, что они действительно являются официальными и безопасными.

## Важная информация

На данный момент репозитории и проекты, выпущенные до 15.08.2024, не подписаны. Однако мы планируем исправить это в будущем и будем работать над тем, чтобы подписать все предыдущие версии. На данный момент подпись доступна только для новых файлов.

## Как проверить подпись

1. Убедитесь, что у вас установлен [GPG](https://gpg4win.org/download.html).
2. Загрузите файл и соответствующую подпись.
3. Используйте команду gpg --verify <подпись> <файл> для проверки.

## Проверка подписи с помощью Kleopatra

1. **Установите Kleopatra**: Убедитесь, что у вас установлено приложение Kleopatra. Оно является частью пакета Gpg4win.

2. **Импортируйте публичный ключ**: Если вы еще не сделали этого, импортируйте [публичный ключ разработчика](https://github.com/ErkinKraft/GPG/blob/main/EK%20SoftWare%20(ErkinKraft)_0xA7C9CB81_public.asc), который использовался для подписи файлов.

3. **Загрузите файл и подпись**: Скачайте файл и соответствующую подпись (.sig или .asc).

4. **Откройте Kleopatra**: Запустите приложение Kleopatra.

5. **Проверка подписи**:
   - Перетащите файл и подпись в окно Kleopatra.
   - Выберите файл, который вы хотите проверить, и щелкните правой кнопкой мыши.
   - Выберите опцию «Проверить» или «Verify».

6. **Результаты проверки**: Kleopatra сообщит вам, действительна ли подпись и соответствует ли она загруженному файлу.

### Подписи на GitHub

Кроме того, GitHub автоматически помечает коммиты в репозиториях в зависимости от их статуса подписи
Если у вас возникнут вопросы или потребуется помощь, не стесняйтесь обращаться к нам!

Спасибо за вашу поддержку!

С уважением,  
[EK SoftWare](https://github.com/EK-SoftWare-RU) и [ErkinKraft](https://github.com/ErkinKraft)
