![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/637efd29-3852-4bf1-9beb-dde24fb3c76c)


# Modelo de Machine Learning - Clasificación 

## Escenario 📝
El área de marketing de un banco de Brasil llama a sus clientes y les ofrecen un servicio de depósito a plazo a sus clientes.
Necesitan nuestra ayuda para descubrir cuáles de sus clientes están interesados.

## Tecnologías utilizadas 👨🏽‍💻

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-blue.svg?style=for-the-badge&logo=Matplotlib&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)



## Etapas del algoritmo

## Configuración del ambiente
> [!IMPORTANT] 
> Si lo ejecutan de manera local, se requiere correr la siguiente línea de código para instalar las tecnologías requeridas:
> ```
> 
> ```

## Obtención, análisis, limpieza y tratamiendo de los datos 📁🕵️‍♂️🧹

Fué laborioso... pero logramos descifrar y entender sus datos. 
Aquí te dejamos un resumen del procedimiento pero si querés verlo a detalle te invitamos a revisar el código del archivo cleaning.ipynb

[<kbd> <br> Link al archivo <br> </kbd>][KBD]

[KBD]: /cleaning.ipynb

El Dataframe original posee la siguiente estructura 

![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/989da257-d3a8-4f95-a3ce-fca506143fe6)

Mostramos el análisis de las columnas que quizás mayor relevancia poseen para ver con qué desafíos nos encontramos

![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/061ab00c-9e86-4db0-bfb9-6a16b8bb51ab)

![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/3aafb48a-2dd0-4940-92c8-41363084db67)

![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/ea4fc90c-fd81-42b4-ad24-ebd84a957223)

![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/0f63d92e-3cd7-4c4b-882c-5e5471a1d58e)

![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/8c80cff3-7f7e-4d0a-aee4-2d5860315c1a)

![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/ee08196d-c6b9-4228-ad3a-47595f015d7d)

Aplicamos otras técnicas para la limpieza de los datos como:

### Análisis de correlación 

![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/631e4962-1de6-4c58-90c3-64b8ff33d8ab)

### Balanceamiento de los datos 

![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/60b01669-d6f4-4b57-8556-cd996fb149a4)


## Implementación del modelo 🚀

![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/3acb2e8a-2ed4-4aee-97ca-a0b7b153f334)

## Evaluamos el modelo

![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/44a33064-d2e0-4c35-ae41-7fa773b33cb2)

## Testeo del modelo con Cross Validation
Utilizamos Cross Validation para evaluar y comparar sus métricas
![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/93ac1d37-87f9-4f1a-b0d3-e5564b71a44f)

## Optimización del modelo con RandomizeSearchCV

### 1_ Establecemos los parámetros de referencia para la optimización
![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/42b4225e-a0a2-4ea9-9093-03af4fcdee4d)

### 2_ Configuramos los criterios de optimización
![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/e0524a2f-28f9-4f91-bac9-7bbd66f4fe99)

### 3_ Buscamos los mejores parámetros para optimizar nuestro modelo
![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/da1753c6-394e-4da7-80ab-4583b26a0714)

## Implementando el modelo optimizado

![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/a5946773-5094-4a75-b6f4-66eff8234bfd)

![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/9a0c8f03-d079-4f80-b5fd-256560b769b6)

## Conclusiones

![image](https://github.com/pabloing93/bank-suscribes-predictions/assets/32267303/b63c7908-f373-4495-91ca-119599de2100)

