### Пример: пресмятане на лице на квадрат със страна **а**

За пример да вземем следната програма, която прочита цяло число от конзолата, умножава го по него самото (вдига го на квадрат) и отпечатва резултата от умножението. Така можем да пресметнем лицето на квадрат по дадена дължина на страната:

```csharp
Console.Write("a = ");              
var a = int.Parse(Console.ReadLine());
var area = a * a;
Console.Write("Square area = ");
Console.WriteLine(area);
```

Ето как би работила програмата при квадрат с размер на страната 3:

![](/assets/chapter-2-images/00.Square-area-01.jpg)

Опитайте да въведете грешно число, например "**hello**". Ще получите съобщение за грешка по време на изпълнение (exception). Това е нормално. По-късно ще разберем как можем да прихващаме такива грешки и да караме потребителят да въвежда число наново.

#### Тестване в Judge системата

Тествайте решението си тук: [https://judge.softuni.bg/Contests/Practice/Index/504#0](https://judge.softuni.bg/Contests/Practice/Index/504#0).