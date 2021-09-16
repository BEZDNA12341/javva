# Отчёт о тестировании код Intellege IDEA

## Краткое описание

07/09/2021 - 09.09.2021 приложения Intellege IDEA.

На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты:
[Сыллка на дефекты](https://github.com/BEZDNA12341/javva/issues/1)

## Описание процесса тестирования


В качестве тестовых данных использовались данные:
* [Тут ссылка на источник](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/MERGED.md) : А если точнее то [Вот](https://github.com/netology-code/javaqa-code/blob/master/1.2_programming/variables/src/Main.java) 
  
public class Main {
  public static void main(String[] args) {
  int price = 2_000_000_000;
  int count = 500_000_000;
  int total = price + count;
  System.out.println(total);
  }
  }

Ожидаемый результат: java intellege IDEA складывает всю сумму,и выдаёт ответ 2_000_500_000

  Тестирование производилось в следующем окружении:

* Intel(R) Core(TM) i5-7200U CPU @ 2.50GHz 2.70 GHz
  64-разрядная операционная система, процессор x64
  Windows 10 Домашняя для одного языка
  21H1
* openjdk version "11.0.11" 2021-04-20
  OpenJDK Runtime Environment AdoptOpenJDK-11.0.11+9 (build 11.0.11+9)
  OpenJDK 64-Bit Server VM AdoptOpenJDK-11.0.11+9 (build 11.0.11+9, mixed mode)