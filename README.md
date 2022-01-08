# Домашнее задание к занятию «2.2. Testability, автотесты, введение в ООП: объекты и методы»

## Задача №3 (повышенной сложности) - "Дифференцированный кредитный калькулятор"

### Легенда

Вам поручили написать кредитный калькулятор, который "считает как на сайте". Но формулы, естественно, не дали.

Вам нужно провести небольшой анализ и написать свой `CreditPaymentService`, который умеет рассчитывать ежемесячный платёж.

Параметры, их количество, типы, а также формулу вам необходимо определить исходя из скриншотов ниже.

Обратите внимание: на тех же данных ваш сервис должен считать так же*.

Примечание*: это очень важный момент - если Заказчик вам даёт примеры, то обязательно следите за тем, что эти примеры в вашем приложении (а позже и в тестах/авто-тестах) проверяются и работают правильно! Если вы этого не сделаете, получите от Заказчика негатив в стиле "я же вам специально примеры предоставил, вы почему не могли на них проверить?!" и общую характеристику непрофессионала.

Чтобы это продемонстрировать, в `Main` создайте объект и 3 раз вызовите его метод `calculate`. Результаты каждого вызова выводите в консоль.

Скриншоты для решения задачи (важно - это не реальный сервис!):

![](pic/one-year.png)

![](pic/two-years.png)

![](pic/three-years.png)


<details>
  <summary>Подсказка</summary>
  
  Подсказки смотреть не хорошо 😈!
  
  Но раз уж вы посмотрели, то вот она подсказка: есть аннуитетные и дифференцированные платежи. Наверное, стоит посмотреть, по каким формулам они считаются.
</details>