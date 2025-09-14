# 402-JS-PHP-PYTHON-C++
---
### 1. Overview

JS,PHP,PY script languages\
C++ compiled language

2. Syntax

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
### 2. Variables

JS

```js
let a = 5;
const b = 2;

let c = a < b;

...

let imie = 'Jan';

document.write('Hello ' + imie);
```
---
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

if a > b
	print("a jest większe od b")
```


C++
```cpp
const int myNum = 15;
cout<<myNum;
---

### 3. Arays

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

### 3. Operators
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

### 4. Conditions
```js
if(){

```

```php
if($a < 2){
	...
}
```
### 5. Iterations

### 6. OOP



### ONLINE EDITORS
- ALL : https://www.w3schools.com/tryit/ , https://replit.com/
- JS : https://codepen.io/
- PY : https://www.online-python.com/
- C++ : https://www.onlinegdb.com/online_c++_compiler


### TUTORIALS
[Full PHP 8 Tutorial - Learn PHP The Right Way In 2023](https://youtu.be/sVbEyFZKgqk)
[kursphp.com](https://kursphp.com/nauka-php-online/)
