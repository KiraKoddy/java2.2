# Отчёт о тестировании Precision
## Краткое описание

11.08.2021 - 11.08.2021 было проведено функциональное тестирование Precision.
На тестирование затрачено: 1,5 часа

* В результате тестирования выявлены следующие дефекты:

[Итоговая сумма бонуса считается не корректно](https://github.com/KiraKoddy/java2.2/issues/1)

## Описание процесса тестирования

В качестве тестовых данных использовались [данные задачи №2](https://github.com/netology-code/javaqa-homeworks/tree/master/programming):
```
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```

## Тестирование производилось в следующем окружении:

* Версия: 2004 ОС: Windows 10 Pro, 64-бит
* Версия Java "11.0.11"
