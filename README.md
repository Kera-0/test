<h3>С++ 3 модуль лекции</h3>
<details><summary>Лекция 2</summary>

   *1. Язык С++ компилируемый, код в нем сразу превращаеться в испольняемые файлы, которые напрямую поступают к процессору.*
    
   *2. Компиляторы превращают код в понятный для компьютера язык(два самых популярных: clang++ и g++)*
    
   *3. Программа сначало запускает функция main(), потом все отсальное.*
    
   ```C++
   int main {
    
   }
   ```
   **Вывод:** 
    
   ![](https://github.com/Kera-0/test/blob/main/%D0%A4%D0%AB%D0%A4%D0%AB%D0%A4%D0%AB%D0%92%D0%AB.PNG)
   ```C++
   int foo {
    
   }
   ```
   **Вывод:** 
    
   ![](https://github.com/Kera-0/test/blob/main/%D0%BE%D1%88%D0%B8%D0%B1%D0%BA%D0%B0.PNG)
   ![](https://github.com/Kera-0/test/blob/main/%D1%86%D0%B9%D1%86%D0%B9%D1%86%D0%B9.PNG)
    
   *4. int пишем перед main т.к она возращает число.*
    
    
    
   *5. возращает одно и тоже*
   ```C++
   int main () {
      return 0;
   }
   ```
   ```C++
   int main () {
        
   }
   ```
   *6. Через return, повилось понимать, что  программа завершилась успешно,елси она возращает 0 код, и другое в ином случае.*
    
   *7. `#include <iostrem>` - для доступа к механизмам ввода (как import в питоне)*
    
   * 1 `std::cin >>` ввод объекта
   * 2 `std::cout <<` вывод объекта 
   * 3 `<< "/n";` или ` << std::endl;` - перенос на новую строку
   * 4 все переменные надо определять на старет, переменная не может поменять свой тип в С++ 
   * 5 int знаковое число(`int a;`)
   *6 `''` - используеться для вывода одного символа `"для ввода стрки"`, иначе будте ошибка(`"ф"` - это не одна буква т.к `''` поддерживает только ASCII) 

  *8) `if` должен быть с `()` и из-за отсутсвия `{}` могут быть ошибки*

  **Пример:**
```C++
#include <iostrem>
int main() {
    int a;
    std::cin >> a;
    if (a % 2 == 0) {
        std::cout << a << "even\n";
    } else {
        std::cout << a << "odd\n";
    }
}

```
*9) bool отвечают только за `true` и `false`*

10) Разница `a++` и `++a`;
```C++
#include <iostrem>
int main() {
    int a = 123;
    std::cout << a++;    
}
```

**Вывод: 123** 

```C++
#include <iostrem>
int main() {
    int a = 123;
    std::cout << ++a;    
}
```

**Вывод: 124** 

11) цикл бесконечный
```
#include <iostrem>
int main() {
    for (;;) {
        std::cout << "1 ";
    }
}
```

**Вывод: 1 1 1 ... 1 1 1 ...

    
12) Если мы хотим чтобы переменные были доступны только в определенном блоке, то
```
#include <iostrem>
int main {


    {
        int a = 5;
    }
    {
        int a;
        std::cout << a;
    }
}
```
**Вывод: число из неинициализированная памяти т.к это две разные переменные а**

13) с начало выпольняеться один раз потом проверяет условие на while
```
do {

} while (true);

```
14) switch в a передаем переменную,она сравниваеться с case, в switch нельзя создавать переменную и если не написать break, то прогрмма выведет все начиная с подходящего case
![](https://github.com/Kera-0/-lecture-notes/blob/main/awqwq.PNG)
15) `a << c` это мы число a умножаем на 2 в степени с
16) `&&` `||` - булевый оператор. 
17) `&` `|` - битовый оператор.



















</details>

<details><summary>Лекция 3</summary>
  
  ![](https://github.com/Kera-0/-lecture-notes/blob/main/32312.PNG)

  0) в С++
  
  ![](https://github.com/Kera-0/-lecture-notes/blob/main/git%201.PNG)
  
  1) `auto` - автоматическое определенние типа

  ![](https://github.com/Kera-0/-lecture-notes/blob/main/git%202.PNG)
  
  2) нельзя `void n = 5`
  
  ![](https://github.com/Kera-0/-lecture-notes/blob/main/git%203.PNG)
  
  3) байт - минимальная адресуемая единица памяти
  
  4) `signed` - число со знаком, `unsigned` - без знаковое число
  
  5) 









  
</details>
