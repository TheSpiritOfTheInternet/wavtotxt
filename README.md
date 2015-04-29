# Wav to txt

Дана програма розроблена для представлення звуку який зписаний в wav 16 bit в числовому значеннні. Для цього було використано мову програмування С# і бібліотеку NAudio. 

```sh
using (WaveFileReader pcm = new WaveFileReader(@"D:\\5.wav"))
```
В цій частині коду ми вказуємо шлях до файлу я кий ми будемо обробляти.
```sh
string path = @"D:\\5.txt";
```
В цій частині коду ми вказуємо шлях до текстового файлу в який ми будемо записувати наші дані. 
###Перевірка роботи
Можна порівняти роботу програми вписавши дані які ми отримали в Excel з роботою програми Audacity:

![alt text](https://github.com/TheSpiritOfTheInternet/wavtotxt/blob/master/img.PNG?raw=true "Результат роботи програми.")
