# RPN-Calculator
Calculator for Android using Reverse Polish Notation.
В калькуляторе преусмотрен ряд правил не позволяющих пользователю вводить некорректные данные.
Калькулятор поддерживает операции сравнения - "<", "≤", ">", "≥", результатом данных выражений являетс логическое значение "true" или
"false". Также реализован тернарный оператор (<условие> ? <первый операнд> : <второй операнд>), <условие> должно быть логическим выражением
т.е. содержать один оператор сравнения. Допускается свободная вложенность тернарных выражений, однако, во избежание неоднозначности,
в случае если вы хотите вложить тернарное выражение в качестве ПЕРВОГО операнда другого тернарного оператора, нужно выделить его скобками,
например - вместо 1<2?1<3?1:3:2 , надо записать - 1<2?(1<3?1:3):2 , в иных случаях вложенности тернарных операторов, скобки необязательны,
Однако крайне желательны, потому как улучшается читаемость выражения. Так же следует помнить, что приоритет тернарного оператора "?:"
ниже приоритета любых других операторов, и поэтому тернарная операция будет выполняться в последнюю очередь.
