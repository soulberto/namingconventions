# Convenciones de nombramiento

Formas de nombrar los diferentes artefactos

| Nombre de Objeto | Tipo de objeto | Ejemplo                |
| :--------------: | -------------- | ---------------------- |
|  RenewalPoliciy  | Batch          | RenewalPoliciy.cls     |
| UpdateOperation  | Job            | UpdateOperationJob.cls |
|  RenewalPolicy   | Test           | RenewalPolicyTest.cls  |
|     SendMail     | Queue          | SendMailQueue.cls      |
|     Account      | Trigger        | AccountTrigger.cls     |

|       Nombre de archivos        | Descripción                                                                                                                                                                                                                                                                                  | Ejemplo          |
| :-----------------------------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- |
|         Nombre de clase         | Los nombres de las clases deben ser únicos, comenzando con una letra mayúscula. NO debe contener guiones bajos o espacios (excepto el prefijo y el sufijo). Los nombres de las clases deben ser sustantivos en casos mixtos, con la primera letra de cada palabra de intervalo en mayúsculas | RenewalPoliciy   |
| Nombre de variable y parámetros | Las variables deben estar con una primera letra minúscula. Las palabras internas comienzan con letras mayúsculas. Los nombres variables deben ser cortos y significativos. Concretamente debe ser estilo camelCase                                                                           | updateAccounts   |
|        Nombre de método         | Los métodos deben ser verbos, en casos mixtos con la primera letra en minúsculas, con la primera letra de cada palabra interna en mayúsculas. Se deben usar palabras completas y el uso de acrónimos y abreviaturas debe ser limitado                                                        | updateAccounts() |
|            Contantes            | Los nombres de las variables declaradas en las constantes de clase deben estar en mayúsculas con palabras separadas por guiones bajos ("\_")                                                                                                                                                 | ACCOUNT_LIMIT    |
