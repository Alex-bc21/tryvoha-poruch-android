# Тривога поруч — виджет 1.0.5

<!-- download-and-share -->
Tryvoha Poruch: Android home-screen widget showing local air-alert status in Ukraine. Android 8+; Ukrainian interface.

### Скачать и установить

- **[TryvohaPoruch-Phone-1.0.5.apk](https://github.com/Alex-bc21/tryvoha-poruch-android/releases/download/v1.0.5/TryvohaPoruch-Phone-1.0.5.apk)**

[Полные исходники](https://github.com/Alex-bc21/tryvoha-poruch-android/releases/download/v1.0.5/TryvohaPoruch-1.0.5-source.zip) · [Все версии и контрольные суммы](https://github.com/Alex-bc21/tryvoha-poruch-android/releases)

Откройте ссылку APK на телефоне, скачайте файл и подтвердите установку средствами Android. Перед установкой проверьте требования и ограничения ниже; новые версии устанавливайте поверх старой с той же подписью, чтобы сохранить настройки.

Это предварительные версии для ознакомления и тестирования. Для скачивания публичных файлов регистрация на GitHub не нужна.

**Поделиться:** отправьте [ссылку на этот проект](https://github.com/Alex-bc21/tryvoha-poruch-android) — здесь будут актуальное описание и ссылки на версии. [Сообщить об ошибке](https://github.com/Alex-bc21/tryvoha-poruch-android/issues).
<!-- /download-and-share -->

Домашний виджет Android и постоянный индикатор статуса тревоги. Показывает город и локальный статус по геолокации, а также свежие опубликованные сообщения об угрозах.

[Скачать APK и исходники](https://github.com/Alex-bc21/tryvoha-poruch-android/releases/tag/v1.0.5).

Предварительная архивная версия от сентября 2026 года. Android 8+ (API 26). Пакет `com.sasha.tryvohaporuch`, versionCode 6. Это самостоятельная сборка, отличная от пакета `ua.yermolenko.tryvoha` в Play Console; не является обновлением поверх Play-версии.

Сохранён исходный подписанный APK. Его подпись и целостность проверены, исходники приложения успешно компилируются, ThreatRepositorySelfTest проходит. Работу с текущими сетевыми источниками, GPS и фоновыми обновлениями на устройстве заново не проверяли. Информационный индикатор не заменяет официальное оповещение; ориентируйтесь на официальные сигналы и указания служб.

## Сборка и установка

Полный публичный проект — `TryvohaPoruch-1.0.5-source.zip`. Linux/macOS: JDK 17, Android SDK Platform 35 и Build Tools 35.0.0; задайте ANDROID_SDK_ROOT и выполните `bash build-apk.sh`. Скрипт создаст собственный локальный ключ, если его нет. Оригинальный ключ подписи не опубликован. APK со своей подписью не обновит оригинальный поверх прежней установки.

В исходниках есть отдельный модуль Wear OS 1.1.1 (`wear`), но APK этого модуля в данном релизе отсутствует. APK Phone предназначен для телефона.

Установите APK на телефон, разрешите геолокацию и уведомления, добавьте виджет через меню домашнего экрана. [Руководство](USER-GUIDE.md), [данные](PRIVACY.md), [проверка](VERIFICATION.md).

