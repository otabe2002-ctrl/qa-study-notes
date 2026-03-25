### Работа с Android Studio

### Эмулятор с поддержкой Play Market

[![Скриншот_1_задание_3.png](https://i.postimg.cc/023mKfv7/Скриншот_1_задание_3.png)](https://postimg.cc/RN7qjwN0)

[![photo_2026_03_01_11_45_33.jpg](https://i.postimg.cc/MTPX26KV/photo_2026_03_01_11_45_33.jpg)](https://postimg.cc/LYPmjMP8)

---

### Активация раздела для разработчика

Сделал на эмуляторе.
Шаги воспроизведения:
Настройки -> About emulated device -> Build number(10 кликов) -> Pop оповещение "Теперь вы разработчик"

Developer options:
Настройки -> System -> Developer options

[![photo_2026_03_01_11_45_31.jpg](https://i.postimg.cc/wvf38qTh/photo_2026_03_01_11_45_31.jpg)](https://postimg.cc/ftdMYhdL)

---

### Logcat

[![photo_2026_03_01_11_45_28.jpg](https://i.postimg.cc/RFsq5SVw/photo_2026_03_01_11_45_28.jpg)](https://postimg.cc/YGFtQwFS)

[![скрин_логов.png](https://i.postimg.cc/jd9NnXTf/скрин_логов.png)](https://postimg.cc/svY1t5vf)

---

### Краткая пошаговая инструкция по созданию симулятора в XCode

1. **Открой Devices and Simulators**
   В Xcode: Window > Devices and Simulators (Cmd+Shift+2).
   Внимание: Если окно пустое — проверь интернет для скачивания runtime; не путай с реальными устройствами (они справа).
2. **Создай новый симулятор**
   Кликни "+" внизу слева.
   Device Type: Выбери модель (iPhone 16 Pro, iPad Pro) — для теста бери свежую, как iPhone 15+.
   OS Version: iOS 18+ — если нет, Xcode предложит скачать (5–10 ГБ, жди индикатора).
   Внимание: Назови уникально (например "iPhone 16 iOS18"), иначе дубли не создастся; проверь свободное место на диске (~20 ГБ).
3. Создай и проверь
   Клик "Create".
   Симулятор появится в списке — кликни Play (треугольник), чтобы запустить.
   Внимание: Если ошибка "Download required" — Xcode > Settings > Platforms, скачай runtime вручную, перезапусти Xcode.
4. Используй в проекте
   В toolbar Xcode (рядом Run) выбери симулятор из dropdown > Run (Cmd+R).
   Внимание: Для разных OS/iOS — создавай отдельно; удали ненужные правым кликом > Delete, чтобы не засорять (~10 ГБ каждый).

   Готово — тестируй app! Если завис — Terminal: `xcrun simctl erase all` для очистки.
