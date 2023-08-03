# Создание подключения к {{ yq-full-name }}

{% note info %}

Для создания подключения требуется [сервисный аккаунт](../../../iam/concepts/users/service-accounts.md) с [ролью](../../../iam/operations/sa/assign-role-for-sa.md) `{{ roles-editor }}` на каталог, в котором создано [соединение](../../../query/concepts/glossary.md#connection) {{ yq-full-name }}. 

{% endnote %}

Чтобы создать подключение к {{ yq-full-name }}:

1. Перейдите на [страницу подключений](https://datalens.yandex.ru/connections).
1. Нажмите кнопку **Создать подключение**.
1. Выберите подключение **{{ yq-full-name }}**.
1. Укажите параметры подключения:

   * **Облако и каталог**. Выберите каталог, в котором создано соединение {{ yq-full-name }}.
   * **Сервисный аккаунт**. Выберите существующий [сервисный аккаунт](../../../iam/concepts/users/service-accounts.md) или создайте новый.
   * **Время жизни кеша в секундах**. Укажите время жизни кеша или оставьте значение по умолчанию.
   * **Уровень доступа SQL запросов**. Позволяет использовать произвольный SQL-запрос для [формирования датасета](../../concepts/dataset/settings.md#sql-request-in-datatset).

1. Нажмите кнопку **Создать подключение**.
1. Введите имя подключения и нажмите **Создать**.

{% include [datalens-check-host](../../../_includes/datalens/operations/datalens-check-host.md) %}