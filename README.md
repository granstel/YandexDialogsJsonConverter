## YandexDialogsJsonConverter
Конвертор для Яндекса.Диалоги(Алисы) в json

В проекте полный набор структур аналогичный как в Api Яндекса.Диалоги(Алисы) для получения данных от Api и для отправки ответа.
Проверка данных на соответствие требований Api перед отправкой ответа.

###### YandexDialogsJsonConverter.Api:
- **GetRequest(value)**  - Конвертирует json-запрос в "объект";
- **SetResponse(value)**  - Конвертирует ответ "объект" в json.
- **SetResponseCheck(value, out Error[])** – проверяет данные на соответствие требований Api и конвертирует ответ "объект" в json.
