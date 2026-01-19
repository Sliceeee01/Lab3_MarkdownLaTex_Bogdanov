# Требования к программе:
##### Имя файла: `FormatDemo.cs`
##### Логика :
   Запрашивает у пользователя **два числа**
   Выполняет **их сложение**
   Выводит результат в **форматированном виде** 
___

### Пример структуры кода с комментариями в стиле Markdown: 

```csharp
Console.Write("Введите первое число: ");
double number1 = Convert.ToDouble(Console.ReadLine());
Console.Write("Введите второе число: ");
double number2 = Convert.ToDouble(Console.ReadLine());
double sum = number1 + number2;
Console.WriteLine($"**Результаты операций: {sum}**");
```