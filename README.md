# Aerial Shell — downloads

Aerial Shell is a shell for FL Studio: a catalog of your projects, a scanner, a player, kits, project moving and backups.
Windows 10/11, 64-bit.

**Download:** [latest release](../../releases/latest) → `AerialShell-Setup-vX.Y.Z.exe`.
The SHA-256 of each build is in `SHA256SUMS.txt` next to it and in `latest.json`.

## Windows SmartScreen warning

The installer is not code-signed yet, so Windows may show "Windows protected your PC" / "Unknown publisher".
To continue: **More info → Run anyway**.
Before running, compare the file's SHA-256 with `SHA256SUMS.txt`:

```
certutil -hashfile AerialShell-Setup-vX.Y.Z.exe SHA256
```

If the hashes differ, do not run the file.

## Editions

- **Lite** — free, no key needed.
- **Pro** — one-time purchase. A key is a `license.json` file tied to your email; it works offline.
  To get one, message [@aer95net on Instagram](https://www.instagram.com/aer95net/).

Updating or reinstalling doesn't touch your data: the database and projects live in the home folder you choose on first run, settings and the key in `%LocalAppData%\AerialLibrary`.

---

# Aerial Shell — загрузки

Aerial Shell — оболочка для FL Studio: каталог проектов, сканер, плеер, киты, переезд проектов и бэкапы. Windows 10/11, 64 бит.

**Скачать:** [последний релиз](../../releases/latest) → `AerialShell-Setup-vX.Y.Z.exe`.
SHA-256 каждой сборки — в `SHA256SUMS.txt` рядом с файлом и в `latest.json`.

## Предупреждение Windows SmartScreen

Установщик пока не подписан сертификатом, поэтому Windows может написать «Система Windows защитила ваш компьютер» /
«Неизвестный издатель». Чтобы продолжить: **Подробнее → Выполнить в любом случае**.
Перед запуском сверьте SHA-256 файла с `SHA256SUMS.txt`:

```
certutil -hashfile AerialShell-Setup-vX.Y.Z.exe SHA256
```

Хеши не совпали — файл не запускайте.

## Издания

- **Lite** — бесплатно, ключ не нужен.
- **Pro** — разовая покупка. Ключ — файл `license.json`, привязан к email, работает без интернета.
  Получить: написать [@aer95net](https://www.instagram.com/aer95net/) в директ Instagram.

Обновление и переустановка не трогают данные: база и проекты лежат в папке программы, которую вы выбираете при первом запуске, настройки и ключ — в `%LocalAppData%\AerialLibrary`.
