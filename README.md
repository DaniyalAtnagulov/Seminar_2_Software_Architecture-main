# Урок 2. Объектно-ориентированные паттерны
## Задание 1. Прислать реализацию 2-ух любых Паттернов.

Порождающие паттерны (Creational Patterns):

Фабричный метод (Factory Method): Он относится к этой категории. Этот паттерн предоставляет интерфейс для создания объектов, но позволяет подклассам выбирать класс создаваемых объектов. То есть он делегирует ответственность за создание экземпляра подклассам.
_
Абстрактная фабрика (Abstract Factory): Предоставляет интерфейс для создания семейств взаимосвязанных объектов без указания их конкретных классов.
_
Строитель (Builder): Позволяет создавать сложные объекты шаг за шагом. Подходит, когда объект имеет множество параметров и конфигураций.
_
Прототип (Prototype): Позволяет создавать новые объекты путем копирования существующих объектов, предоставляя метод клонирования.
_
Одиночка (Singleton): Гарантирует, что у класса есть только один экземпляр, и предоставляет глобальную точку доступа к этому экземпляру.
_
## Задание 2. Познакомиться с другими типами паттернов (задание по желанию)

Структурные паттерны (Structural Patterns):

Адаптер (Adapter): Позволяет объектам с несовместимыми интерфейсами работать вместе.
_
Мост (Bridge): Разделяет абстракцию и реализацию так, чтобы они могли изменяться независимо.
_
Компоновщик (Composite): Позволяет сгруппировать объекты в древовидную структуру для представления часть-целое.
_
Декоратор (Decorator): Позволяет динамически добавлять новую функциональность объектам без изменения их кода.
_
Фасад (Facade): Предоставляет унифицированный интерфейс к группе интерфейсов в подсистеме.
_
Прокси (Proxy): Предоставляет заместитель для другого объекта для контроля доступа к нему.
_
Поведенческие паттерны (Behavioral Patterns):

Цепочка обязанностей (Chain of Responsibility): Позволяет передавать запросы последовательно по цепочке обработчиков.
_
Команда (Command): Инкапсулирует запрос как объект, позволяя параметризовать клиентов с операциями, выполнять запросы в очереди и поддерживать отмену операций.
_
Итератор (Iterator): Предоставляет способ последовательного доступа ко всем элементам объекта, не раскрывая его внутренней структуры.
_
Посредник (Mediator): Определяет объект, инкапсулирующий способ взаимодействия множества объектов. Способствует слабой связанности
системы.
_
Снимок (Memento): Позволяет зафиксировать и восстановить внутреннее состояние объекта.
_
Наблюдатель (Observer): Определяет зависимость "один ко многим" между объектами так, что при изменении состояния одного объекта все зависящие от него объекты уведомляются и обновляются.
_
Состояние (State): Позволяет объекту изменять свое поведение при изменении его внутреннего состояния. Кажется, будто объект меняет свой класс.
_
Стратегия (Strategy): Определяет семейство алгоритмов, инкапсулирует каждый из них и делает их взаимозаменяемыми.
_
Шаблонный метод (Template Method): Определяет скелет алгоритма, оставляя некоторые шаги на усмотрение подклассов.
_
Посетитель (Visitor): Позволяет добавлять новые операции для объектов без изменения их классов.