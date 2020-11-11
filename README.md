# OBD-2020

***ІD:*** UC_1.1

***НАЗВА:*** Створити обліковий запис.

***УЧАСНИКИ:*** Респондент, Система

***ПЕРЕДУМОВИ:*** Обліковий запис відсутній

***РЕЗУЛЬТАТ:*** Новий обліковий запис.

***ВИКЛЮЧНІ СИТУАЦІЇ:***

* **EX.001.001.** Респондент вже зареєстрований у системі.
* **EX.001.002**. Респондент ввів неіснуючу електронну пошту.

***ОСНОВНИЙ СЦЕНАРІЙ:***

![uml](http://www.plantuml.com/plantuml/png/VLD3mfn145t_kaF5vYvshX3RrcGLsxQJ6_HqHf-lK7MZl5STQzXyglgMdshjEDawVUJmsF1P_QXTkwIDrbffHxjQsUMpOyD-OcnueRxJO9TrW2CvHay5fu9WN6cDIxbTaV4EyTGksMMxY3FNxRaz6B-8s9zu4TUxMceuIxWFE58dDhi2EBkgDPRAV-684qLyFsizDWnY7dTKkuBrO3SqWEoVHXRg2ms-6h5oFpdeOjgsQ_PSErXyBhvVs8EfMf09wzLCBWPmSUFkJ50tTX4RVOsWlwNTcO9PESKUp9GziuxiE70O2vTWfqlneXsgvrKQSBdFfoto1CYAJ29FWh_dENmrraMYbod9RzmLZJoNx83scc0OqX1WUFyzP49Z7kqvD3-mfp_Zk5z7uH0eHu-rziZ90_lsjsJ2shKhy5ee-XQ-UqXZmEmt7vKrwsVFdJkFtvydysUJxfExWNoFbz72ztCwObQQYVQz193f2JnnDv3upNc1YpT4WvidOoh-Y_-MzRstoK3BX5Aa5BxsPsItEYtQZ6iu9xXSf8Izh1NtM5T8lybsOYne0XJ-znAvu0fRcFxUeb3vXnhSgR-sQECJA09tW94gjRAumBOzzoGkkv281lfHIwyD7yHZn_c_VC_HtNXYlm00)

***ІD:*** UC_1.2

***НАЗВА:*** Редагувати обліковий запис.

***УЧАСНИКИ:*** Респондент, Система.

***ПЕРЕДУМОВИ:*** Респондент зареєстрований в системі.

***РЕЗУЛЬТАТ:*** Змінено обліковий запис.

***ВИКЛЮЧНІ СИТУАЦІЇ:***
* **EX.002.001.** Нові дані, введені респондентом, вже є в системі.

***ОСНОВНИЙ СЦЕНАРІЙ:***

![uml](http://www.plantuml.com/plantuml/png/ZP75LMrH44Jd9ufUxuy_DiET571tjyi8bp7kJWJFtLAepeXgtE6wx2vPfsRUwvtp5YOdt19k4TLrv9535X54aTMD9VVmtvNX2W7TG890Ya-7GYOWVCuIpoEbc-8p0Gu64DPDX1vvnzz1fFMOQ8uV4qWAucJofkKhf-sTFP6D8eF0qgCLPSn4jv3JDMHC7IUy7zCl8Npz89ipvesm7flqrutAtkQaoOy9o_zO_GH1UgrHE6mi5PxJVjtnveaEwR6kwOwfXaXRN8jvB1RG7ihTrBGtA7EZmoEU_6jggkLM9hYaTmnf9AnynvGqjXGK5PNmB2vmPSzf621iYT-aANTSqUaPvse6fmPisUKU)

***ІD:*** UC_1.3

***НАЗВА:*** Видалити обліковий запис.

***УЧАСНИКИ:*** Респондент, Система.

***ПЕРЕДУМОВИ:*** Респондент зареєстрований в системі.

***РЕЗУЛЬТАТ:*** Видалено обліковий запис.

***ВИКЛЮЧНІ СИТУАЦІЇ:***
Відсутні.

***ОСНОВНИЙ СЦЕНАРІЙ:***

![uml](http://www.plantuml.com/plantuml/png/ZL6rMGPH4CotYlqkfW6SKj08jmYN3DS8hU3ShONPZXZSuO-UZRtPeSMbaOMbvUafMSKTOjj2YmOr8iIeRNjLdjwb1zVmR1iP0GLtvqgCfzpNXBSeR4STd28ZqKD97B4gVFDHsYKAxWA-vegKWFPHoEcbv_tZZk0O5RpLPnz4JmwsYyOsKNsHPYucEz8lsWr2D2hlyhP3Wry-rOFJ9qhq6DJsbOY0IanNFWfnMtSfNyj7dvR7Y143ActoCdcD80Y-fkhjiAdRBvfFVVrOoDlFcOLYVpRQAy9vpSw934tCZ3yELHy0)

***ІD:*** UC_1.4

***НАЗВА:*** Авторизація.

***УЧАСНИКИ:*** Користувач, Система.

***ПЕРЕДУМОВИ:*** Користувач зареєстрований в системі.

***РЕЗУЛЬТАТ:*** Авторизація користувача.

***ВИКЛЮЧНІ СИТУАЦІЇ:***
* **EX.004.001.** Користувач ввів дані, яких немає у системі.
* **EX.004.002.** Користувач не зареєстрований.

***ОСНОВНИЙ СЦЕНАРІЙ:***

![uml](http://www.plantuml.com/plantuml/png/ZL53OWHH45r7TnXiusGJErU8RQkpYctRki3OtNs5LpTALMrY31g5fry-PNHC6jCZmsd9ixY6HOk8q18jqmfyyD36R5goJgGb5-AE2ylIHeoVJXqmuN7mimaBDcAqud3X1JuwHrJcN4M2-GJ5Gn09U6O5vW8UmOR9LGz2jC9GjAhK2SQGhiwRIhPAvqgtJkTqKVIpoa8SyxE5029SttNqP8nq30mxXCF1wZoyOY5EkqN_TVB0n06UyY78kmpxcwS77GgAULga0u6CmT9IZ0TDBY-fB0J4EU-lCTBecD7Zc1pewpSSxjhQ2luKEd0B2o744H4xpQEEclhCxEny_kTald_BpHJUGyrAyq2OLfJtQppmC1b_-IZ7nkLUtZFQpMV-2W00)

***ІD:*** UC_1.5

***НАЗВА:*** Підтвердження облікового запису.

***УЧАСНИКИ:*** Користувач, Система.

***ПЕРЕДУМОВИ:*** Запит на підтвердження облікового запису.

***РЕЗУЛЬТАТ:*** Підтверджений обліковий запис.

***ВИКЛЮЧНІ СИТУАЦІЇ:***
* **EX.005.001.** Помилка підтвердження облікового запису.

***ОСНОВНИЙ СЦЕНАРІЙ:***

![uml](http://www.plantuml.com/plantuml/png/LL33OGLH5DqFUXYiOzjf8RQjoIgsRISLV1lJmhaTvRuN_cSUrIuuVVFEujIahYpZ4MbQHvGsQ9Esu8UNzfPrHRxGbNAy8KJht7UGHX1HVdHim6yWyVtbra04NWCktI98c_3Bzs7QebFQGnH9NO7B51kyJi2B559qXcI5hWZoZoyKX924TrdoPU049TArmUG-9FWgpYi_GyKaBIFpVyQQdd66ZFcnaL77i9kRwxYK6tZcjs4Xb7-aEwUDfjRitDmYxddPmk3ChD1GEpGzo4by0W00)
