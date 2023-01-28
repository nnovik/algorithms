## F. Отрезки времени

Вам задан набор отрезков времени. Каждый отрезок задан в формате HH:MM:SS-HH:MM:SS, то есть сначала заданы часы, минуты и секунды левой границы отрезка, а затем часы, минуты и секунды правой границы.

Вам необходимо выполнить валидацию заданного набора отрезков времени. Иными словами, вам нужно проверить следующие условия:

часы, минуты и секунды заданы корректно (то есть часы находятся в промежутке от 0 до 23, а минуты и секунды — в промежутке от 0 до 59);
левая граница отрезка находится не позже его правой границы (но границы могут быть равны);
никакая пара отрезков не пересекается (даже в граничных моментах времени).
Вам необходимо вывести YES, если заданный набор отрезков времени проходит валидацию, и NO в противном случае.

Вам необходимо ответить на 𝑡 независимых наборов тестовых данных.

Неполные решения этой задачи (например, недостаточно эффективные) могут быть оценены частичным баллом.

### Входные данные
Первая строка входных данных содержит одно целое число 𝑡 (1≤𝑡≤10) — количество наборов тестовых данных. Затем следуют 𝑡 наборов.

Первая строка набора содержит одно целое число 𝑛 (1≤𝑛≤2⋅10<sup>4</sup>) — количество отрезков времени. В следующих 𝑛 строках следуют описания отрезков.

Описание отрезка времени задано в формате HH:MM:SS-HH:MM:SS, где HH, MM и SS — последовательности из двух цифр. Заметьте, что никаких пробелов в описании формата нет. Также ни в одном описании нет пробелов в начале и конце строки.

### Выходные данные
Для каждого набора тестовых данных выведите ответ — YES, если заданный набор отрезков времени проходит валидацию, и NO в противном случае. Ответы выводите в порядке следования наборов во входных данных.
