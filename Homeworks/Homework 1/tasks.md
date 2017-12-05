
1) Напишете програма, която чете от конзолата две цели числа n, m. Програмата трябва да
изведе на екрана броя на числата в интервала [n, m] на които сборът на делителите е
просто число.
Пример за сбор на делителите:
28 -> 1 + 2 + 4 + 7 + 14 = 28
16 -> 1 + 2 + 4 + 8 = 15

2) Да се състави програма, при която предварително са въведени естествени числа в
двумерен масив 4*4 елемента. Програмата да извежда резултат от проверката какво е
съотношението на най-голямата сума по редове спрямо най-голямата сума по колони.
Пример:
1 , 2, 3, 4
5, 6, 7, 8
9, 10, 11, 12
13, 14, 15, 16
Изход:
Biggest sum from rows 58
Biggest sum from columns 40
Maximum sum from rows are > then maximum sum from columns

3) Дадени са два едномерни масива с естествени числа от интервала (0..1000). Да се
състави програма, която проверява дали първият масив е подмножество на втория.
Първият масив не трябва да съдържа повтарящи се числа. Множество - съвкупност от
неповтарящи се елементи.
Пример:
2,1,5,4,6
1,2,3,4,5,6,7,18,7,11
Изход: YES

4) Проверете дали елементите на масив е зигзагообразна нагоре. Това е редица при която
елементите изпълняват условието: N1 < N2 > N3 < N4 > N5 <..
Пример: 1 3 2 4 3 7

5) Въведете квадратна матрица с големина n^2, проверете дали въведената матрица е
симетрична. Симетрична означава, че елементите на позиции (i, j) и (j, i) са еднакви
Примери:
● вход: n = 3
4 -5 2
-5 0 1
2 1 8
изход: Yes.
● вход: n = 4
1 2 3 4
5 6 7 8
9 0 0 0
3 2 1 -1
изход: No.

6) Даден ни е двумерен масив. Въвеждаме от клавиатурата брой на редове (числов тип без
знак), брой на колони(числов тип без знак), след което попълваме масива с произволни
числа. По въведено число програмата трябва да връща :

- ако числото не е в масива - съобщение за грешка
- ако числото е в масива - брой на съседите му.
  Пример:
  3 3
  1 2 3
  4 5 6
  7 8 9
  8
  5 съседа
  Пример 2:
  3 3
  1 2 3
  4 5 6
  7 8 9
  100
  ERROR(съобщение за грешка)