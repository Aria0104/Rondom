```C#
// я не сделала проверку на дурочка поскольку можно испоьзовать только условные конструкции, код с проверкой внизу
Random random = new Random();
int secretNumber = random.Next(1, 101);
Console.WriteLine("Угодай число от 1 до 100, у вас есть 5 попыток");

Console.WriteLine("Первая попытка");
int pop1 = Convert.ToInt32(Console.ReadLine());

    if (pop1 == secretNumber)
{ Console.WriteLine("Поздравяю вы угадали"); }

else { Console.WriteLine("Вы не угодали попробуете еще"); }


Console.WriteLine("Вторая попытка");
int pop2 = Convert.ToInt32(Console.ReadLine());

if (pop2 == secretNumber)
    { Console.WriteLine("Поздравяю вы угадали"); }

    else { Console.WriteLine("Вы не угодали попробуете еще"); }


Console.WriteLine("Третья попытка");
int pop3 = Convert.ToInt32(Console.ReadLine());

if (pop3 == secretNumber)
{ Console.WriteLine("Поздравяю вы угадали"); }

else { Console.WriteLine("Вы не угодали попробуете еще"); }


Console.WriteLine("Четвертая попытка");
int pop4 = Convert.ToInt32(Console.ReadLine());

if (pop4 == secretNumber)
{ Console.WriteLine("Поздравяю вы угадали"); }

else { Console.WriteLine("Вы не угодали попробуете еще"); }


Console.WriteLine("Пятая попытка");
int pop5 = Convert.ToInt32(Console.ReadLine());

if (pop5 == secretNumber)
{ Console.WriteLine("Поздравяю вы угадали"); }

else { Console.WriteLine("Вы не угодали, ваши попытки закончились"); }

/* С проверкой. Я решила использовать цикл while, который будет повторяться пока не будет введено правельное число
Random random = new Random();
int secretNumber = random.Next(1, 101);
Console.WriteLine("Угодай число от 1 до 100, у вас есть 5 попыток");

int Proverka()
{
    int input; 
    while (true)
    {
        input = Convert.ToInt32(Console.ReadLine());
        if (input >= 1 && input <= 100)
            return input;
        Console.WriteLine("Число должно быть от 1 до 100. Попробуйте снова:");
    }
}


Console.WriteLine("Первая попытка");
int pop1 = Proverka();

if (pop1 == secretNumber)
{ Console.WriteLine("Поздравяю вы угадали"); }

else { Console.WriteLine("Вы не угодали попробуете еще"); }


Console.WriteLine("Вторая попытка");
int pop2 = Proverka();

if (pop2 == secretNumber)
{ Console.WriteLine("Поздравяю вы угадали"); }

else { Console.WriteLine("Вы не угодали попробуете еще"); }


Console.WriteLine("Третья попытка");
int pop3 = Proverka();

if (pop3 == secretNumber)
{ Console.WriteLine("Поздравяю вы угадали"); }

else { Console.WriteLine("Вы не угодали попробуете еще"); }


Console.WriteLine("Четвертая попытка");
int pop4 = Proverka();

if (pop4 == secretNumber)
{ Console.WriteLine("Поздравяю вы угадали"); }

else { Console.WriteLine("Вы не угодали попробуете еще"); }


Console.WriteLine("Пятая попытка");
int pop5 = Proverka();

if (pop5 == secretNumber)
{ Console.WriteLine("Поздравяю вы угадали"); }

else { Console.WriteLine("Вы не угодали, ваши попытки закончились"); } */

```
