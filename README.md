# Aerial Shell — downloads

Aerial Shell is a shell for FL Studio: a catalog of your projects, a scanner, a player, kits, a project mover and a backup.
Windows 10/11, 64-bit.

**Download:** [latest release](../../releases/latest) → `AerialShell-Setup-vX.Y.Z.exe`.
The SHA-256 of each build is in `SHA256SUMS.txt` next to it and in `latest.json`.

## Windows SmartScreen warning

The installer is not code-signed yet, so Windows may show "Windows protected your PC" / "Unknown publisher".
This is expected for this build. To continue: **More info → Run anyway**.
Before running, compare the file's SHA-256 with `SHA256SUMS.txt`:

```
certutil -hashfile AerialShell-Setup-vX.Y.Z.exe SHA256
```

If the hashes differ, do not run the file.

## Editions

- **Lite** — free, no key needed.
- **Pro** — one-time purchase. A key is a `license.json` file tied to your email; it works offline.
  To get one, message [@aer95net on Instagram](https://www.instagram.com/aer95net/).

Your data lives outside the program folder (`%LocalAppData%\AerialLibrary`): updating or reinstalling does not touch it.

---

# Aerial Shell — загрузки

Aerial Shell — оболочка для FL Studio: каталог проектов, сканер, плеер, киты, переезд проектов и бэкап. Windows 10/11, 64 бит.

**Скачать:** [последний релиз](../../releases/latest) → `AerialShell-Setup-vX.Y.Z.exe`.
SHA-256 каждой сборки — в `SHA256SUMS.txt` рядом с файлом и в `latest.json`.

## Предупреждение Windows SmartScreen

Установщик пока не подписан сертификатом, поэтому Windows может написать «Система Windows защитила ваш компьютер» /
«Неизвестный издатель». Для этой сборки это ожидаемо. Чтобы продолжить: **Подробнее → Выполнить в любом случае**.
Перед запуском сверьте SHA-256 файла с `SHA256SUMS.txt`:

```
certutil -hashfile AerialShell-Setup-vX.Y.Z.exe SHA256
```

Хеши не совпали — файл не запускайте.

## Издания

- **Lite** — бесплатно, ключ не нужен.
- **Pro** — разовая покупка. Ключ — файл `license.json`, привязан к вашей почте, работает без интернета.
  Получить: написать в личку [@aer95net в Instagram](https://www.instagram.com/aer95net/).

Данные живут вне папки программы (`%LocalAppData%\AerialLibrary`): обновление и переустановка их не трогают.
