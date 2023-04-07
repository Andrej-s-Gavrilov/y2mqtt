# y2mqtt
## План
1. Прочитайте концепцию управления умным домом (https://yandex.ru/dev/dialogs/smart-home/doc/concepts/general-concept.html#general-concept).
2. Реализуйте авторизационный сервис на основе стандарта OAuth 2.0 (https://tools.ietf.org/html/rfc6749) для авторизации пользователей.
3. Реализуйте API, который принимает на вход запросы в формате платформы умного дома (https://yandex.ru/dev/dialogs/smart-home/doc/reference/resources.html) и преобразует их в запросы к вашему API.
4. Ознакомьтесь с типами устройств (https://yandex.ru/dev/dialogs/smart-home/doc/concepts/device-types.html) и их умениями (https://yandex.ru/dev/dialogs/smart-home/doc/concepts/capability-types.html).
5. Опишите устройства в формате платформы умного дома.
6. Настройте логирование запросов от платформы умного дома (в каждом запросе передается заголовок X-Request-Id). Это понадобится, чтобы изучать инциденты и проблемы.
7. Создайте и опубликуйте навык умного дома (https://yandex.ru/dev/dialogs/smart-home/doc/start.html).

From https://yandex.ru/dev/dialogs/smart-home/doc/concepts/quick-start.html
