**Автор**: DK

# **Внимание!** Все параметры команд вводятся через пробел
# Вводить [ и ] не нужно! Квадратные скобки означают, что параметры не всегда используются!

## Категория **party**
Команды:

1. set - Установить переключатель
2. enable - Включить переключатель
3. disable - Выключить переключатель
4. switch - Переключить переключатель

### **Синтаксис для команды set**
set ID VALUE [MAP_ID EVENT_ID]

ID должно быть числом (номер переключателя) или строкой (название локального переключателя)

VALUE должно быть: true (включить) или false (выключить)

Дополнительные параметры (только если используете локальный переключатель)!

MAP_ID должно быть числом (номер карты)

EVENT_ID должно быть числом (номер события)

Пример1: set 1 true (глобальный переключатель)

Пример2: set a true 1 1 (локальный переключатель А)

### **Синтаксис для команд enable, disbale, switch**
NAME ID [MAP_ID EVENT_ID]

NAME должно быть названием команды (enable, disbale или switch)

ID должно быть числом (номер переключателя) или строкой (название локального переключателя)

Дополнительные параметры (только если используете локальный переключатель)!

MAP_ID должно быть числом (номер карты)

EVENT_ID должно быть числом (номер события)

Пример1: enable 1 (глобальный переключатель)

Пример2: disable a 1 1 (локальный переключатель А)