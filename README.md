Отчёт о тестировании **Money Transfer**    
Краткое описание     
**13.07.2021 - 13.07.2021** было проведено функциональное тестирование программного кода **Money Transfer**.

***Входные данные:***

1. текущий баланс счёта клиента - переменная типа int, значение - 2_000_000_000 (два миллиарда рублей)    
1. сумма перевода - переменная типа int, значение - 500_000_000 (пятьсот миллионов рублей)     
1. переменная для хранения итогового значения - тип int      

**Код:**   

    class Main {
      public static void main(String[] args) {
        int balance = 2_000_000_000;
        int coming = 500_000_000;
        int total = balance + coming;
        System.out.println(total);
      }
    }    

На тестирование затрачено: **1 час**

****В процессе тестирования использовались следующие артефакты****   

Intellij IDEA

**В результате тестирования выявлены следующие дефекты**

Программа компилирует не верное значение   

[Ссылка на  issue](https://github.com/alexboom85/Money/issues/new)

****Тестирование производилось в следующем окружении****

Ноутбук HP Pavilion,Windows 10, x64     
Openjdk version "11.0.11" 2021-04-20
