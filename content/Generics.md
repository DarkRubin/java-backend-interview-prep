## Generics

#### 1. Что такое дженерики? Для чего нужны?
Дженерики - параметризованные типы в Java

- Что это? Позволяют создавать классы, интерфейсы и методы с типами, заданными как параметры
- Зачем нужны? Позволяют использовать один класс для разных типов данных (`List<String>`, `List<Integer>`)

#### 2. Что такое сырые типы?
Сырые типы - это использование обобщенных классов без указания типов

#### 3. Что такое вайлдкард
Вайлдкарды - это символ ‘?’, который используется для обозначения неизвестного типа в дженериках

#### 4. Расскажите про принципе PECS
- Producer. Используется для чтения (? extends T)
- Consumer. Используется для добавления (? super T)
- Оба действия. Использовать конкретный тип, а не wildcard

#### 5. Расскажите про класс Optional
Optional - Класс-обертка. Он помогает избежать ошибок, связанных с null