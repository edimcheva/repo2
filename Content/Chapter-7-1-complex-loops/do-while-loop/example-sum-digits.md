### Пример: сумиране на цифрите на число

Да се сумират цифрите на цяло **положително** число **n**. Например, ако **n = 5634**, то резултатът ще бъде: 5 + 6 + 3 + 4 = **18**.

Можем да използваме следната идея, за да решим задачата:

* Създаваме променливата **`n`**, на която присвояваме стойност, равна на въведеното от потребителя число.
* Създаваме втора променлива - **`sum`**, чиято начална стойност е 0. Нея ще използваме за изчислението и съхранението на резултата.
* За условие на цикъла ще използваме **`n > 0`**, тъй като след всяко изчисление на резултата в тялото на цикъла, ще премахваме последната цифра от **`n`**.
* В тялото на цикъла:
   * Присвояваме нова стойност на **`sum`**, която е резултат от събирането на текущата стойност на **`sum`** с последната цифра на **`n`**.
   * Присвояваме нова стойност на **`n`**, която е резултат от премахването на последната цифра от **`n`**.
* Извън тялото на цикъла отпечатваме крайната стойност на сумата.

![](/assets/chapter-7-images/09.Sum-digits-01.png)

<table><tr><td><img src="/assets/alert-icon.png" style="max-width:50px;" /></td>
<td><code><strong>n % 10</strong></code>: <b>връща</b> последната цифра на числото <code><strong>n</strong></code>.<br>
<code><strong>n / 10</strong></code>: <b>изтрива</b> последната цифра на <code><strong>n</strong></code>.</td>
</tr></table>

#### Тестване в Judge системата

Тествайте решението си тук: [https://judge.softuni.org/Contests/Practice/Index/514#8](https://judge.softuni.org/Contests/Practice/Index/514#8).
