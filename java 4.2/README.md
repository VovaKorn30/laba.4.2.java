
## Функціональність програми

Ця програма розроблена для декодування зашифрованих повідомлень, які можна закодувати двома різними методами:  заміною голосних  і заміною приголосних
 Він визначає спосіб кодування  кожного слова та відновлює вихідний текст



### Методи

- `decodeVowels(String input)`: Декодує повідомлення, закодоване методом заміни голосних, де голосні літери a, e, i, o, u замінюються на відповідні числа 1, 2, 3, 4, 5.
  
- `decodeConsonants(String input)`: Декодує повідомлення, закодоване методом заміни приголосних, де кожний приголосний замінюється на наступний приголосний в послідовності.


1. **Чому була створена ця програма?**
   - Для декодування зашифрованих повідомлень у форматі, який застосовує різні методи кодування.

2. **Чому потрібно декодувати повідомлення?**
   - Декодування повідомлень дозволяє отримати зрозумілу інформацію з зашифрованого тексту.

3. **Чому використовується StringBuilder?**
   - Використання StringBuilder забезпечує ефективні маніпуляції з рядками та покращує продуктивність програми при зміні текстових даних.

## Тести

Програма включає набір тестів для перевірки правильності функціонування методів декодування:

1. ** `decodeVowels`**
   - - Перевірте правильність розшифрованого повідомлення  методом заміни голосних

2. ** `decodeConsonants`**
   - Перевірте правильність розшифрованого повідомлення  методом заміни приголосних


