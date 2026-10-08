# Yandex AutoPlay — AndroidIDE

Оригинальная Яндекс Музыка: `ru.yandex.music`
Android: 10–11
Задержка после загрузки: 8 секунд.

Сборка:
1. Распакуйте ZIP.
2. Откройте корневую папку проекта в AndroidIDE.
3. Дождитесь синхронизации Gradle.
4. Build → Assemble Debug APK.
5. APK: `app/build/outputs/apk/debug/app-debug.apk`

После установки один раз откройте Yandex AutoPlay. Если магнитола имеет настройки автозапуска/энергосбережения, разрешите автозапуск для приложения.

Некоторые прошивки могут блокировать запуск Activity из фонового BOOT_RECEIVER или программную Media Play-команду.
