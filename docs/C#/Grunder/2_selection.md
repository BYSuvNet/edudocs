---
title: Selektion
description: If, else if och else är grundläggande kontrollstrukturer i C#.
icon: material/call-split
---

# Selektion

If, else if och else är grundläggande kontrollstrukturer i C# som används för att styra flödet av programmet baserat på villkor. De gör det möjligt att utföra olika kodblock beroende på om ett visst villkor är sant eller falskt.

```csharp
int number = 10;

if (number > 0)
{
    Console.WriteLine("Numret är positivt.");
}
else if (number < 0)
{
    Console.WriteLine("Numret är negativt.");
}
else
{
    Console.WriteLine("Numret är noll.");
}
``` 

