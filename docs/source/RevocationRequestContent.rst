﻿RevocationRequestContent
========================

Объект предназначен для работы с метаданными запроса на аннулирование документа 
и является производным объектом от :doc:`BaseContent <BaseContent>`.

Свойства объекта
----------------


- **Signer** (объект :doc:`Signer <Signer>`, чтение) - данные подписанта документа

- **Comment** (строка, чтение/запись) - комментарий

- **Type** (строка, чтение) - тип контента (возвращает строку "RevocationRequest")


Методы отсутствуют
