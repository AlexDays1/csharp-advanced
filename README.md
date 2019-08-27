﻿# 1.Упражнения: Първи стъпки в програмирането

Задачи за упражнение в клас и за домашно към курса [&quot;Основи на програмирането&quot; @ СофтУни](https://softuni.bg/courses/programming-basics).

Тествайте решенията си в **judge**  **системата** :[https://judge.softuni.bg/Contests/Compete/Index/1010](https://judge.softuni.bg/Contests/Compete/Index/1010)

1. 1.Конзолна програма &quot;Hello SoftUni&quot;

Напишете **конзолна**  **C#**  **програма** , която отпечатва текста &quot; **Hello SoftUni**&quot;.

1. Стартирайте Visual Studio.
2. Създайте нов конзолен проект: [File] [New] [Project].
3. Изберете от диалоговия прозорец [Visual C#] [Windows] [Console Application]и дайте подходящо име на проекта, например&quot; **HelloSoftuni**&quot;:
4. Намерете секцията **Main(string[] args)**. В нея се пише програмен код (команди) на езика C#.
5. Придвижете курсора между отварящата и затварящата скоба **{ }**.
6. Натиснете **[Enter]**след отварящата скоба **{**.
7. Напишете следния програмен код (команда за печатане на текста **&quot;**** Hello SoftUni&quot;**):

| Console.WriteLine(&quot;Hello SoftUni&quot;); |
| --- |

Кодът на програмата се пише отместен навътре с една табулацияспрямо отварящата скоба **{**.

1. **Стартирайте** програмата с натискане на **[Ctrl+F5]**. Трябва да получите следния резултат:
2. **Тествайте** решението на тази задача в онлайн judge системата на СофтУни. За целта първо отворете [https://judge.softuni.bg/Contests/Compete/Index/1010#0](https://judge.softuni.bg/Contests/Compete/Index/1010#0). Влезте с вашето потребителско име в СофтУни. Ще се появи прозорец за изпращане на решения за задача&quot; **Hello SoftUni**&quot;. Копирайте сорс кода от Visual Studio и го поставете в полето за изпращане на решения:
3. **Изпратете решението** за оценяване с бутона [Submit]. Ще получите резултата след няколко секунди в таблицата с изпратени решения в judge системата:

1. 2.Конзолна програма &quot;Expression&quot;

Напишете **конзолна**  **C#**  **програма** , която пресмята и отпечатва стойността на следния **числен израз** :

| (3522 + 52353) \* 23 - (2336 \* 501 + 23432 - 6743) \* 3 |
| --- |

Забележка: не е разрешено да се пресметне стойността предварително (например с Windows Calculator).

1. Направете нов C# конзолен проект с име &quot; **Expression**&quot;.
2. Намерете метода &quot;**static void Main(string[] args)**&quot;и влезте в неговото тяло между **{** и **}**.
3. Сега трябва да напишете кода, който да изчисли горния числен израз и да отпечата на конзолата стойността му. Подайте горния числен израз в скобите на командата **Console.WriteLine()**:

1. Стартирайте програмата с **[Ctrl+F5]**и проверете дали получавате следното число:

1. Тествайте решението си в judge системата: [https://judge.softuni.bg/Contests/Practice/Index/1010#1](https://judge.softuni.bg/Contests/Practice/Index/1010#1).

1. 3.Числата от 1 до 20

Напишете C# конзолна програма, която отпечатва числата от 1 до 20 на отделни редове на конзолата.

1. Създайте конзолно C# приложение с име &quot; **Nums1To20**&quot;:

1. Напишете 20 команди **Console.WriteLine()**, една след друга, за да отпечатате числата от 1 до 20.

1. **Тествайте** вашето решение на задачата в judge системата.
2. Можете ли да напишете програмата по **по-умен начин** , така че да не повтаряте 20 пъти една и съща команда? Потърсете в Интернет информация за &quot;[**for loop C#**](https://www.google.com/search?q=for+loop+C%23)&quot;.

1. 4.Лице на правоъгълник

Напишете C# програма, която прочита от конзолата две числа **a** и **b** , въведени от потребителя,пресмята и отпечатва **лицето на правоъгълник** със страни **a** и **b**. Примерен вход и изход:

| **a** | **b** | **area** |
| --- | --- | --- |
| 2 | 7 | 14 |
| 7 | 8 | 56 |
| 12 | 5 | 60 |

1. Направете конзолна C# програма. За да прочетете двете числа, използвайте следния код:

| staticvoid Main(string[] args){    double a = double.Parse(Console.ReadLine());    double b = double.Parse(Console.ReadLine());                // TODO: calculate the area and print it} |
| --- |

1. Допишете програмата по-горе, за да пресмята лицето на правоъгълника и да го проверява.
2. Тествайте решението си в judge системата.
