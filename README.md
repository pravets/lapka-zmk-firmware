# Wellum 36 for Lapka

Реализация раскладки [Wellum 36](https://github.com/braindefender/wellum) для клавиатуры [Lapka](https://github.com/braindefender/lapka)

В этой ветке используется Dongle, поэтому прошивка состоит из трёх частей:
- `wellum36_left`
- `wellum36_right`
- `wellum36_dongle`

При изменении раскладки, прошивать нужно только `dongle`.

> Файлы для `left` и `right` можно прошить один раз, т.к. матрица подключения не меняется.
