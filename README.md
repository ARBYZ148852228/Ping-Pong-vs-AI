🏓 GPT PIN-PONG

🎮 Простая аркадная игра на Python с использованием **Pygame**. Это классическая версия "Пинг-Понга", где вы можете играть против друга или встроенного ИИ 🤖. Добавлены звуки, победа при 10 очках и постепенное ускорение мяча для большей динамики!

📋 Описание
Игра запускается в окне 1200x720 пикселей. У каждого игрока есть ракетка, мяч отскакивает от ракеток и краёв. Побеждает тот, кто первым наберёт **10 очков**. После этого игра завершится сообщением о победителе. 🏆

Также реализованы:
- 🧠 ИИ для правого игрока
- 🎵 Звуки отскока мяча и набора очков
- ⚡ Постепенное ускорение мяча при каждом столкновении
- 🎯 Отображение счёта на экране

🎮 Управление
| 👤 Игрок | 🎹 Клавиши |
|---------|------------|
| Игрок 1 (слева) | `W` (вверх), `S` (вниз) |
| Игрок 2 (справа, если `--human`) | `↑` (вверх), `↓` (вниз) |

🧠 Режим ИИ
🤖 По умолчанию правой ракеткой управляет ИИ. Он следует за мячом, когда тот находится на его половине поля. Если вы хотите играть вдвоём, добавьте параметр `--human` при запуске игры.

🧱 Особенности
- 📏 Размер окна: `1200x720`
- 🔢 Счёт игроков отображается сверху
- 🎼 Поддержка звуков (файлы `bounce.wav`, `score.wav`)
- 🏁 Игра завершается при достижении 10 очков одним из игроков
- 🚀 Мяч ускоряется при каждом отскоке — не расслабляйся!
