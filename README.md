<h2>Требования к проекту</h2>
<hr>
<h2>Содержание</h2><br>
    1. Введение<br>
    2. Требования пользователя<br>
    2.1 Программные интерфейсы<br>
    2.2 Интерфейсы пользователя<br>
    2.3 Характеристики пользователей<br>
    3. Системные требования<br>
    3.1 Функциональные требования<br>
    3.2 Нефункциональные требования<br>
    3.2.1 Атрибуты качества<br>
    3.2.1.1 Ограничения<br>
    3.2.1.2 Бизнес-правила<br>
    3.2.1.3 Требования к интерфейсу пользователя<br>
    3.2.1.4 Требования важные для разработчика<br>

<h2>1. Введение</h2><br>
В данном документе описаны функциональные и нефункциональные требования к приложению Калькулятор. Программа предназначена для студентов и работников технической и инженерной сфер. В отличии от стандартного калькулятора поддерживаются операции с комплексными числами и их преобразование в различные формы.

<h2>2. Требования пользователя</h2><br>
<h3>2.1 Программные интерфейсы</h3><br>
Приложение разрабатывается на языке Java и должно быть платформонезависимым.<br>

<h3>2.2 Интерфейс пользователя</h3><br>
Окно приложения содержит поле ввода/вывода информации, цифры, математические операции (сложение, вычитание, умножение, деление, возведение в степень, скобки, вычислить, синус и косинус) и операции перевода комплексных чисел в другую форму (тригонометрическую, показательную и алгебраическую).<br>

<img src='/Images/window.png' width='200'>

<h3>2.3 Характеристики пользователя</h3><br>
Данное приложение представленно для студентов и работников технической и инженерной сфер.<br>

<h2>3. Системные требования</h2><br>
Приложение должно быть платформонезависимым.<br>

<h3>3.1 Функциональные требования</h3><br>
Приложение должно выполнять арифметические операции над целыми, дробными и комплексными числами (сложение, вычитание, умножение, деление, возведение в степень, преобразование комплексных чисел, синус и косинус).<br>

<h3>3.2 Нефункциональные требования</h3><br>
<h3>3.2.1 Атрибуты качества</h3><br>
<h3>3.2.1.1 Ограничения</h3><br>
Приложение работает на версии java 8 и выше.

<h3>3.2.1.2 Бизнес-правила</h3><br>
Приложение должно:
<ul>
    <li>выполнять валидацию данных;</li>
    <li>отображать не менее 12 значащих цифр;</li>
    <li>адекватно реагировать на ввод пользователя (отображать вводимые цифры/операции, отображать результат вычисления, кратко сообщать о математических ошибках).</li>
</ul>

<h3>3.2.1.3 Требования к интерфейсу пользователя</h3><br>
Атрибуты, важные для пользователей:
<ul>
    <li><ul>удобство и простота использования:
        <li>интуитивность интерфейса;</li>
        <li>одно окно без каких-либо скрывающих элементов (вкладок, раскрывающихся списков, полос прокрутки и т.д.);</li>
        <li>всем кнопкам должны соответствовать быстрые клавиши.</li>
    </ul></li>
</ul>

<h3>3.2.1.4 Требования важные для разработчика</h3><br>
Атрибуты, важные для разработчиков:
<ul>
    <li><ul>лёгкость в эксплуатации: </li>
        <li>вложенность вызываемых функций не должна превышать 10 уровней;</li>
        <li>для каждого программного модуля непустые комментарии в соотношении к исходному коду должны составлять как минимум 0,1;</li>
    </ul></li>
    <li>тестируемость: максимальная цикломатическая сложность модуля (количество логических ответвлений в модуле исходного кода) не должна превышать 50.</li>
    <li>производительность: результаты вычислений должны выводиться в течении 5 секунд.</li>
    <li>устойчивость к сбоям: приложение должно продолжать корректную работу после ошибок валидации данных.</li>
</ul>
