﻿ExtendedSigner
==============

Объект предназначен для редактирования информации о лице, подписавшем документ.


Свойства объекта
----------------

- **BoxId** (строка, чтение/запись) - идентификатор ящика организации, которую представляет подписант

- **CertificateThumbprint** (строка, чтение/запись) - отпечаток сертификата подписанта

- **SignerDetails** (объект :doc:`ExtendedSignerDetails <ExtendedSignerDetails>`, чтение) - информация о подписанте

Если заполнены поля BoxId и CertificateThumbprint, поле SignerDetails заполнять не нужно. В этом случае вся информация о подписанте будет взята с сервера Диадок.
Если поля BoxId и CertificateThumbprint не заполнены, поле SignerDetails является обязательным для заполнения.


Методы отсутствуют


.. toctree::
   :name: Auto
   :hidden:

   ExtendedSignerDetails <ExtendedSignerDetails>