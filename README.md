 ***Виды ошибок.***

 **Ошибка** (error) – это действие человека, которое порождает неправильный результат.

**Дефект**, **Баг** (Defect, Bug) – недостаток компонента или системы, который может привести к отказу определенной функциональности (невозможности выполнить требуемую функцию, например, неверный оператор или определение данных).

Дефект, обнаруженный во время исполнения программы, может вызвать отказ отдельного компонента или всей системы.

При исполнении кода программы дефекты, заложенные еще во время его написания, могут проявиться: программа может не делать того, что должна или наоборот делать то, чего не должна – происходит сбой.

**Сбой** (failure) – несоответствие фактического результата (actual result) работы компонента или системы ожидаемому результату (expected result).

**Программная ошибка** — это расхождение между программой и ее спецификацией, причем тогда и только тогда, когда спецификация существует и она правильна.

Отладкой называют процесс локализации и исправления ошибок, обнаруженных при тестировании программного обеспечения.

**Локализация** — это определение оператора/операторов программы, выполнение которого вызвало нарушение вычислительного процесса.

Для исправления ошибки необходимо определить ее причину, т.е. установить оператор или фрагмент, содержащие ошибку. Причины ошибок могут быть как очевидны, так и очень глубоко скрыты.

Сбой в работе программы может являться индикатором наличия в ней дефекта.

Баг существует при одновременном выполнении 3-х условий:
1) Известен ожидаемый результат;
2) Известен фактический результат;
3) Фактический результат существенно отличается от ожидаемого результата.

**Виды ошибок в тестировани:**
1) Ошибки компиляции. Это простые ошибки, которые в компилируемых языках программирования выявляет компилятор (программа, которая преобразует текст на языке программирования в набор машинных кодов).
2) Ошибки компоновки. Ошибки связаны с разрешением внешних ссылок.
3) Ошибки выполнения (RUNTIME Error). Ошибки, которые обнаруживают операционная система, аппаратные средства или пользователи при выполнении программы.
4) Ошибки определения данных или неверное определение исходных данных. Они могут появиться во время выполнения операций ввода-вывода.

К ним относятся:
* ошибки преобразования;
* ошибки данных;
* ошибки перезаписи.
5) Логические ошибки. Они могут возникать из ошибок, которые были допущены при выборе методов, разработке алгоритмов, определении структуры данных, кодировании модуля.
6) Ошибки накопления погрешностей.

  ***Методы отладки программного обеспечения.***
  
Отладка программы в любом случае предполагает обдумывание и логическое осмысление всей имеющейся информации об ошибке. Большинство ошибок можно обнаружить по косвенным признакам посредством тщательного анализа текстов программ и результатов тестирования без получения дополнительной информации. При этом используют различные методы:
1) Ручного тестирования;
2) Индукции;
3) Дедукции;
4) Обратного прослеживания.

**Методы отлидки программного обеспечения:**

1) Метод ручного тестирования. Отладка программы заключается в тестировании вручную с помощью тестового набора, при работе с которым была допущена ошибка.
2) Метод индукции. В основе отладки системы — тщательный анализ проявлений ошибки. Это могут быть сообщения об ошибке или неверные результаты вычислений.
3) Метод дедукции. Сначала специалисты предлагают множество причин, по которым могла возникнуть ошибка. Затем анализируют их, исключают противоречащие имеющимся данным. Если все причины были исключены, проводят дополнительное тестирование. В обратном случае наиболее вероятную причину пытаются доказать.
4) Метод обратного прослеживания. Эффективен для небольших программ. Начинается с точки вывода неправильного результата. Для точки выдвигается гипотеза о значениях основных переменных, которые могли привести к ошибке. Далее на основании этой гипотезы строятся предположения о значениях переменных в предыдущей точке. Процесс продолжается до момента, пока не найдут ошибку.

***Методы тестирования программного обеспечения***

Программные приложения можно проверить с помощью двух основных типов тестирования, а именно функционального и автоматизированного.

**Функциональное тестирование** — это проверка ПО вручную (без использования автоматизированных инструментов). 

При использовании **автоматизированного тестирования** QA-инженер прописывает сценарии и применяет в работе специализированные приложения.

**Методы тестирования ПО.**

Существует три метода тестирования программного обеспечения:
1) Белый ящик;
2) Черный ящик;
3) Серый ящик.

**Тестирование методом «чёрного ящика»:**

Методика тестирования без глубоких знаний о внутренней работе ПО называется «чёрным ящиком». Специалист не берёт во внимание архитектуру системы и не имеет доступа к исходному коду. Как правило, при выполнении теста с «чёрным ящиком» специалист работает с пользовательским интерфейсом системы, вводя данные и анализируя результат При этом тестировщик не знает, как и где обрабатываются эти данные.

**Тестирование методом «белого ящика»:**

Проверка «белого ящика» — это подробное исследование внутренней логики и структуры кода. Тестирование с использованием этого метода также называют тестированием стекла, или открытым тестированием. Зная, как работает код, эксперт изучает его изнутри и выясняет, какое устройство / блок кода ведёт себя некорректно.

**Тестирование методом «серого ящика»:**

Этот метод представляет собой что-то среднее между двумя предыдущими. При тестировании «серого ящика» специалист должен иметь представление о внутреннем устройстве ПО — но не слишком глубокое. Он ставит себя на место конечного пользователя, но проверяет функционал программы опираясь на понимание её внутреннего устройства.

***Информация взята с следующих сайтов:***
   
1) https://blog.skillfactory.ru/glossary/otladka-debugging/
2) https://qquade.gitbook.io/mdk-handbook/testirovanie-i-podderzhka-programmnykh-modulei/vidy-oshibok.-metody-otladki
3) https://studfile.net/preview/5125263/page:33/
4) https://tquality.ru/blog/tipiurovniimetoditestirovaniyaprogrammnogoobespecheniya/
