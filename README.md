# 402-JS-PHP-PYTHON-C++
---
### 1. Overview

JS,PHP,PY script languages\
C++ compiled language

### 2. Syntax

JS
```js
document.write('Hello JS');

...

document.querySelector('#el').innerHTML = 'Hello injected';
```

PHP
```php
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>PHP Syntax</title>
</head>
<body>
        <h1><?php echo 'Hello PHP'; ?></h1>
</body>
</html>
```

```php
<?php
	echo 'Hello PHP';
	print('Hello PHP');
```

PY 
```python
print("Hello, World!")
```

C++
```cpp
#include <iostream>

using namespace std;

int main()
{
    cout<<"Hello World";

    return 0;
}
```

---
### 3. Variables

JS

```js
let a = 5;
const b = 2;

let c = a < b;

...

let imie = 'Jan';

document.write('Hello ' + imie);
```

PHP
```php
$name = 'Jan';
define("NR_TEL","666666666");

echo "Hello $Jan";

echo 'Hello ' .  $Jan;
echo 'Your tel is ' . $NR_TEL;

...


$x = 1;
$y = $x; // $y = &$x;

$x = 3;

echo $y;

...

<?= "Hello world"?>

```

PY
```python
a = 5
b = 2
```


C++
```cpp
const int myNum = 15;
cout<<myNum;
```

### 4. Arays

JS
```js
let arr1 = [];
const arr2 = new Array(1,2,3,4);
```

PHP
```php
$numbers = [1,2,3,4,5];
$persons = array("Mary" => "Female", "John" => "Male", "Mirriam" => "Female");
```

C++
```cpp
string cars[4];
string cars[4] = {"Volvo", "BMW", "Ford", "Mazda"};
int myNum[3] = {10, 20, 30};

cout << cars[0];
```


### 5. Operators
#### arytmetyczne

- “+” — suma dwóch liczb lub ciągów (“Hello ” + “World” → “Hello World”)
- “-” — różnica dwóch wartości
- “*” — iloczyn wartości
- “/” — iloraz dzielenia
- “%” — modulo, czyli reszta z dzielenia (10 % 3 → 1)

#### porównania

- “==” — równość wartości (bez uwzględnienia typu danych)
- “===” — identyczność (wartości i typu danych)
- “!=” — różność wartości
- “!==” — nieidentyczność wartości lub typu
- “>” oraz “<” — porównują wartości pod względem wielkości
- “>=”, “<=” — porównanie większy lub równy oraz mniejszy lub równy.

#### logiczne
- “&&” — koniunkcja logiczna (AND)
- “!” — negacja logiczna (NOT)
- “||” — alternatywa logiczna (OR), zwana sumą logiczną.

#### pperatory Inkrementacji, Dekrementacji i Przypisania
- $i++ — zwiększenie wartości zmiennej po użyciu w instrukcji,
- ++$i — zwiększenie wartości przed instrukcją,
- $i--, --$i — analogiczne operacje zmniejszające wartość o 1.
Mamy również wygodne operatory przypisania:

- $i += 5 zwiększa wartość zmiennej o 5,
- $i /= 2 dzieli wartość zmiennej przez 2 i przypisuje wynik tej operacji.


### 6. Conditions

JS
```js
if(...){
	...
} else {
	...
}

----

a = 10
b = 5

const c = a > b ? "większe" : "mniejsze"
```
PHP
```php
$uzytkownik = "admin";
$tryb = "pilny";
if ($uzytkownik == "admin" || $tryb == "pilny") 
{ 
  echo "Dostęp możliwy!";
}
else
{ 
  echo "Brak dostępu!";
}

---

$odpowiedz = ($a>5) ? 'Większa od 5' : 'Mniejsza, bądź równa 5';
```
Python
```python
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
else:
  print("a is greater than b")
```
C++
```cpp
int time = 20;
if (time < 18) {
  cout << "Good day.";
} else {
  cout << "Good evening.";
}
```

### 7. Loops
JS
```JS
for (let i = 0; i < 5; i++) {
  text += "The number is " + i + "<br>";
}
```
PHP
```php
for ($x = 0; $x <= 10; $x++) {
  echo "The number is: $x <br>";
}
```

Python
```python
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
```


C++
```cpp
for (int i = 0; i < 5; i++) {
  cout << i << "\n";
}
```

### 8. OOP

PHP
```php
class Fruit {
  // Properties
  public $name;
  public $color;

  // Methods
  function set_name($name) {
    $this->name = $name;
  }
  function get_name() {
    return $this->name;
  }
}

$apple = new Fruit();
$banana = new Fruit();
$apple->set_name('Apple');
$banana->set_name('Banana');

echo $apple->get_name();
echo "<br>";
echo $banana->get_name();
```

---
### ONLINE EDITORS
- ALL : https://www.w3schools.com/tryit/ , https://replit.com/
- JS : https://codepen.io/
- PY : https://www.online-python.com/
- C++ : https://www.onlinegdb.com/online_c++_compiler

---
### ZADANIA

#### ZAD40201
- Przygotuj stronę PHP której wygląd i parametry bedą zdefiniowane w pliku params.php
---

### TUTORIALS
[Full PHP 8 Tutorial - Learn PHP The Right Way In 2023](https://youtu.be/sVbEyFZKgqk)
[kursphp.com](https://kursphp.com/nauka-php-online/)

### LINKS
https://logoipsum.com
