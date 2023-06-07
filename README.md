# Homework3

//Напишите программу, которая принимает на вход пятизначное число и проверяет, является ли оно палиндромом
//Здесь применила новую переменную Bool isPolindrom 

Console.WriteLine("Введите пятизначное число");
int number = Convert.ToInt32(Console.ReadLine());
int X1 = number/10000 % 10;
int X2 = number/1000 % 10;
int X3 = number/100 % 10;
int X4 = number/10 % 10;
int X5 = number % 10;
bool isPolindrom = (X1 == X5 && X2 == X4);
if (isPolindrom)
{
    Console.WriteLine("Число является полиндромом");
}
else
{
   Console.WriteLine("Число не является полиндромом"); 
}


//Напишите программу, которая принимает на вход координаты двух точек и находит расстояние между ними в 3D пространстве.

Console.WriteLine ("Введите A (x)");
int x1 = Convert.ToInt32(Console.ReadLine());
Console.WriteLine ("Введите A (y)");
int y1 = Convert.ToInt32(Console.ReadLine());
Console.WriteLine ("Введите A (z)");
int z1 = Convert.ToInt32(Console.ReadLine())
Console.WriteLine ("Введите B (x)");
int x2 = Convert.ToInt32(Console.ReadLine());
Console.WriteLine ("Введите B (y)");
int y2 = Convert.ToInt32(Console.ReadLine());
Console.WriteLine ("Введите B (z)");
int z2 = Convert.ToInt32(Console.ReadLine());
double res = Math.Round (Math.Sqrt ((x2 - x1) * (y2 - y1) * (z2 - z1));
Console.WriteLine (res);

//Напишите программу, которая принимает на вход число (N) и выдаёт таблицу кубов чисел от 1 до N.

Console.WriteLine ("Введите число");
int num1 = Convert.ToInt32(Console.ReadLine());
int X1 = 1;
if (num1 <= 0)
{
    Console.WriteLine ("Введено некорректное число");
}
else
{
    while (X1 <= num1)
    {
        int res = X1*X1*X1;
         Console.WriteLine (res);
         X1++;
    }
}