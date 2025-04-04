## BUG_MMSRO_004 | Отсутствие обратной связи на кнопках вкладок

### Описание проблемы

Отсутствует визуальная обратная связь при переключении между вкладками. Пользователь не понимает, на какой вкладке находится.

---

### Приоритет

**Уровень:** Medium

> Влияет на интерфейс и вызывает путаницу в навигации.

---

### Среда

| Параметр             | Значение                                                                |
| -------------------- | ----------------------------------------------------------------------- |
| Устройство           | PC                                                                      |
| Операционная система | Windows 11 Pro                                                          |
| Браузеры             | Chrome 134.0.6998.166, Firefox 136.0.2, Edge 134.0.3124.85 (все 64-bit) |
| Версия системы       | 64-bit                                                                  |

---

### Шаги для воспроизведения

1. Перейти на сайт https://modultest1.framer.website
2. Нажать на любую вкладку в верхнем меню

---

### Ожидаемое поведение

Кнопка визуально меняется при активации — изменяется цвет, появляется тень, выделение или анимация.

---

### Фактическое поведение

Нет визуального отклика — пользователь не понимает, какая вкладка активна.

---

### Вложения

- [Видео с демонстрацией проблемы](https://drive.google.com/file/d/199pqW2gBiNDZdMg8JVFJEb3FpiRZyf16/view?usp=sharing)

---

### Предлагаемое решение

Добавить стили активного состояния и эффектов при нажатии на вкладку.

---

### Дополнительная информация

Ошибка наблюдается стабильно в указанной конфигурации и во всех указанных браузерах.
