# Actividad 2

### Pricing en EC2

##### Analítica Computacional para la Toma de Decisiones

---

|     Nombres      |      Apellidos       |     Login     |  Codigo   |
| :--------------: | :------------------: | :-----------: | :-------: |
|     Santiago     | Gonzalez Montealegre | s.gonzalez35  | 202012274 |
| Juliana Carolina |  Cardenas Barragan   | jc.cardenasb1 | 202011683 |

---

---

## 1. Consulte y estime los costos de los recursos en AWS

---

### 1.

Para la estimación de costos, AWS ofrece una calculadora en la página https://calculator.aws. Visite esta página.

![1_1](image/Actividad2-Solución/1_1.png)

---

### 2.

Click en Crear una estimación o Create estimate.

---

### 3.

Busque por ubicación. Seleccione la Región Norte de Virginia.

![1_3](image/Actividad2-Solución/1_3.png)

---

### 4.

En Buscar servicio ingrese EC2.

![1_4](image/Actividad2-Solución/1_4.png)

---

### 5.

La búsqueda filtra los resultados y debe mostrar una caja con una descripción de EC2, un enlace a la página del servicio y un botón Configurar. Haga click en este botón para agregar servicios de este tipo a su estimación de costos.

---

### 6.

Incluya una descripción en el primer campo con los nombres de los integrantes del grupo.

---

### 7.

Como región seleccione N. Virginia.

![1_7](image/Actividad2-Solución/1_7.png)

---

### 8.

Note las diferentes instancias de EC2.

---

### 9.

Inicialmente debe tener seleccionada un tipo de instancia por defecto. Registre el nombre del tipo de instancia seleccionado y sus características en su reporte.

![1_9_1](image/Actividad2-Solución/1_9_1.png)

![1_9_2_](image/Actividad2-Solución/1_9_2.png)

La instancia seleccionada por defecto es:

- Nombre: t4g.nano
- Familia: t4g
- vCPU: 2
- Memoria: 0.5 GiB
- Rendimiento de la Red: Hasta 5 Gigabits
- Almacenamiento: Solamente EBS
- Costo por hora bajo demanda: 0.0042 USD
- Costo potencial efectivo por hora (% de ahorro): 0.0016 (63%)

---

### 10.

En la sección Opciones de pago seleccione Bajo demanda y deje un 100 % de utilización.

---

### 11.

En la parte inferior izquierda encontrará el costo mensual, regístrelo en su reporte.

![1_11](image/Actividad2-Solución/1_11.png)

Para la instancia seleccionada por defecto el costo es de 3.07 USD

---

### 12.

Regrese ahora a la parte superior en los tipos de instancia. Note que las instancias pueden ser de diferentes tipos. Seleccione una instancia optimizada para cómputo y repita el ejercicio. Registre el costo mensual bajo demanda en su reporte.

![1_12_1](image/Actividad2-Solución/1_12_1.png)

![1_12_2](image/Actividad2-Solución/1_12_2.png)

![1_12_3](image/Actividad2-Solución/1_12_3.png)

---

### 13.

Repita el ejercicio anterior con una instancia orientada a memoria. Registre el costo mensual bajo demanda en su reporte.

![1_13_1](image/Actividad2-Solución/1_13_1.png)

![1_13_2](image/Actividad2-Solución/1_13_2.png)

![1_13_3](image/Actividad2-Solución/1_13_3.png)

---

### 14.

Repita el ejercicio anterior con una instancia con GPU. Registre el costo mensual bajo demanda en su reporte.

![1_14_1](image/Actividad2-Solución/1_14_1.png)

![1_14_2](image/Actividad2-Solución/1_14_2.png)

![1_14_3](image/Actividad2-Solución/1_14_3.png)

El costo de la instancia g4ad.xlarge con una utilización del 100% al mes es de 276.33 USD

---

### 15.

Con esta instancia seleccionada modifique el uso de 100 % a 10 horas al mes. Registre el costo mensual bajo demanda en su reporte.

![1_15](image/Actividad2-Solución/1_15.png)
