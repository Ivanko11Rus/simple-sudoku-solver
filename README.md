# Sudoku Solver

This program was created by AI under my careful guidance. 🙂

**Note:** the interface is in Russian, but the instructions below are in
English. The buttons should be fairly self-explanatory.

I vibe-coded the simplest browser Sudoku solver — no external scripts, fonts,
or CDNs, everything inside one HTML file. Opens in modern browsers without
any issues and works without an internet connection.

The layout adapts to desktop, mobile, and tablets.

Simple input: just type digits, pick cells with arrow keys or by clicking.
Auto-advance to the next cell (and to the next row) works, so you can type
the puzzle in blindly.

**To mark an empty cell, type `0`** — or just move to the next cell with an
arrow.

**Keyboard shortcuts.**
- `Backspace` clears the current cell.
- `Enter` presses **«Решить»** (Solve).

When done, press **«Решить»** (Solve) — the last solution is kept in the
second panel (**«Предыдущее решение»**, Previous solution). The program also
highlights contradictions automatically (very handy for occasional single
mistakes).

**Note:** if the grid is partially filled (or the puzzle has multiple
solutions), the solver will still find *a* valid solution — but not
necessarily the one the puzzle author intended. If the grid contains
conflicts, the solver will refuse to run and highlight them.

To reset the board, press **«Очистить»** (Clear).

**Dark theme.** There's a dark theme — tap the cheese-banana / sun icon to
the right of the buttons to switch. (It's actually a moon emoji, but it
does look like a cheese banana.)

After solving, solver-filled digits are green, and digits you entered keep
the default text color (dark in light theme, light in dark theme).

## License

MIT. Enjoy! I hope this program helps you and saves you some time.
Full license text — in the [LICENSE](LICENSE) file.

---
<br>


# Решатель судоку

Данная программа создана ИИ под моим чутким руководством. 🙂

Навайбкодил простейший браузерный решатель судоку — никаких внешних
скриптов, шрифтов и CDN, всё внутри одного HTML-файла. Без проблем
открывается в современных браузерах и работает без интернета.

Вёрстка адаптирована как под компьютер, так и под мобильные устройства
и планшеты.

Простейший ввод: просто вводи цифры и выбирай ячейку стрелками или кликом
мыши. Работает автопереход на следующие ячейки, а также строки — очень
удобно вводить вслепую.

**Чтобы указать пустую ячейку, введите `0`** — или просто стрелкой
перейдите на следующую ячейку.

**Горячие клавиши.**
- `Backspace` очищает текущую клетку.
- `Enter` нажимает **«Решить»**.

В конце ввода нажмите **«Решить»** — последнее решение будет сохранено во
втором поле (**«Предыдущее решение»**). Программа также автоматически
подсветит противоречия (очень помогает при случайных и одиночных ошибках).

**Внимание:** если поле заполнено не до конца (или у головоломки несколько
решений), решатель всё равно найдёт *какое-то* валидное решение — но не
обязательно то, что задумал автор. Если в условии есть конфликты,
решатель откажется запускаться и подсветит их.

Чтобы очистить поле, нажмите **«Очистить»**.

**Тёмная тема.** Есть тёмная тема — тыкайте на иконку сырного банана или
солнца справа от кнопок, чтобы переключить. (На самом деле это эмодзи
луны, но выглядит как сырный банан.)

После решения зелёным будут подсвечены цифры от решателя, чёрным или белым
(в зависимости от темы) — введённые изначально для решения.

## Лицензия

MIT. Наслаждайтесь! Надеюсь, программа поможет Вам и сэкономит время.
Полный текст лицензии — в файле [LICENSE](LICENSE).

---