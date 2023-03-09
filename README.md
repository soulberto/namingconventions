# # Convenciones de nombramiento

A continuación ya recopilación de recomendaciones para el nombrado de diferentes artefactos en el desarrollo de aplicaciones sobre Salesforces:

## Estilo de nombrado de los diferentes artefactos y archivos

| Prefijos | Donde usarlo | Descripción          | Ejemplo de uso                              |
| -------- | ------------ | ------------------- | ------------------------------------------- |
| clb_ins_ | Objetos personalizados, Objetos de Salesforce Estándar, Big Objets, Eventos y cualquier otro tipo de objeto dentro de la estructura de Salesforce que lo permita | Siglas de Cloudblue | Se debe usar en las definiciones de Objetos y Campos Personalizados, por ejemplo: <code>clb_ins_PolicyDetails__c, clb_ins_PolicyEvent__e, clb_ins_TransactionHistory__b</code> |
| ClbIns  | Lightning Web Component (LWC) | Siglas de Cloudblue | <code>ClbInsDraftInsurancePolicy.cls</code> |
| Helper   | Apex         | Código de utilidad  | <code>FTPHelper.cls</code>                  |
| Batch    | Apex         | Batch               | <code>RenewalPoliciyBatch.cls</code>        |
| Job      | Apex         | Job                 | <code>UpdateOperationJob.cls</code>         |
| Test     | Apex         | Test                | <code>RenewalPolicyTest.cls</code>          |
| Queue    | Apex         | Queue               | <code>SendMailQueue.cls</code>              |
| Tigger   | Apex         | Trigger             | <code>AccountTrigger.cls</code>             |

## Estilo de nombrado y convenciones de código

| Nombre de archivos             | Donde usarlo | Descripción                                                                                                                                                                                                                                                                                  | Ejemplo de uso                                           |
| ------------------------------ | ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| Clases e interfaces            | Apex         | Los nombres de las clases deben ser únicos, comenzando con una letra mayúscula. NO debe contener guiones bajos o espacios (excepto el prefijo y el sufijo). Los nombres de las clases deben ser sustantivos en casos mixtos, con la primera letra de cada palabra de intervalo en mayúsculas | <code>public with sharing class RenewalPoliciy {}</code> |
| Variable y parámetros          | Apex         | Las variables deben estar con una primera letra minúscula. Las palabras internas comienzan con letras mayúsculas. Los nombres variables deben ser cortos y significativos. Concretamente debe ser estilo camelCase                                                                           | <code>String accountDescription = '';</code>             |
| Métodos                        | Apex         | Los métodos deben ser verbos, en casos mixtos con la primera letra en minúsculas, con la primera letra de cada palabra interna en mayúsculas. Se deben usar palabras completas y el uso de acrónimos y abreviaturas debe ser limitado                                                        | <code>updateAccounts();</code>                           |
| Contantes y valores inmutables | Apex         | Los nombres de las variables declaradas en las constantes de clase deben estar en mayúsculas con palabras separadas por guiones bajos ("\_")                                                                                                                                                 | <code>final String ACCOUNT_LIMIT = 100;</code>           |

## Citas e información adicional disponible en la web

\* https://quip.com/MW5cAPVwat8k#JCIACA8Q963

\*\* https://www.apexhours.com/salesforce-naming-conventions-best-practices/
