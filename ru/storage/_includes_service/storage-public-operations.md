- [На чтение объектов](../s3/api-ref/object/get.md) в бакете.
- [К списку объектов](../s3/api-ref/bucket/listobjects.md) в бакете.
- На чтение настроек:
    - [CORS](../s3/api-ref/cors/get.md)
    - [Хостинг статического сайта](../s3/api-ref/hosting/get.md)
    - [Жизненные циклы объектов](../s3/api-ref/lifecycles/get.md)

Публичный доступ к каждой операции выдается отдельно. То есть, если вы открыли доступ только на чтение объектов, то операции получения списка объектов и настроек бакета недоступны анонимному пользователю.