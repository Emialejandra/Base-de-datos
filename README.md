PRACTICA 
Paso 1: Crear la base de datos y tabla de prueba 
La base índice y mas.sql ya tenia una tabla creada 
Paso 2: Insertar muchos registros de prueba 
<img width="268" height="272" alt="image" src="https://github.com/user-attachments/assets/917e8f21-2a73-4d79-9e86-f6d9971f16e6" />
Paso 3: Medir tiempo de consulta sin índice 
<img width="602" height="101" alt="image" src="https://github.com/user-attachments/assets/78c7c075-8dc3-4f45-89d4-4f4c694eb94f" />
<img width="720" height="55" alt="image" src="https://github.com/user-attachments/assets/e2c6bb31-6e83-428a-bef6-c450f622d42e" />
Paso 4: Crear un índice en la columna 
<img width="534" height="103" alt="image" src="https://github.com/user-attachments/assets/f4c46af3-36da-4fa4-98b0-d0a6596c7f78" />
Paso 5: Medir tiempo de consulta con índice 
<img width="695" height="53" alt="image" src="https://github.com/user-attachments/assets/0d9665ca-bade-47ec-95dd-6ee55f192b98" />
6.	Declaraciones en procedimientos Investigar: 
•	Qué es DECLARE i INT DEFAULT 1; 
Es una declaración de variable interna del procedimiento almacenado. En el cual la variable se llama i que empezará con 1. 
•	Qué es DECLARE c INT; 
Es otro tipo de declaración de variable, pero sin valor inicial, llamada c de tipo entero que empieza como null. 
•	En qué parte del procedimiento almacenado se usan 
Dentro del bloque BEGIN END, las declaraciones declare deben ir al inicio del bloque antes de cualquier instrucción SET, INSERT, SELEC, etc. 
•	Función del SET dentro de un PROCEDURE 
Sirve para asignar valores variables dentro del procedimiento. 
<img width="602" height="52" alt="image" src="https://github.com/user-attachments/assets/e9f6e6d1-08d5-428d-8d36-c152c3947715" />
REQUERIMIENTOS PRÁCTICOS – ACTIVIDAD COMPLETA 
Los estudiantes deben cumplir TODOS los puntos siguientes: 
1.	Crear Base de Datos Relacional (tomar el script adjunto) Requerimiento: 
•	Crear una base de datos llamada llantas_db con mínimo 4 tablas relacionadas: 
Clientes,productos, ventas, detalle_venta
•	Definir claves primarias y foráneas correctamente. 
<img width="361" height="263" alt="image" src="https://github.com/user-attachments/assets/1698a9fb-20c9-43f9-9bd1-a415ea5de990" />
<img width="475" height="254" alt="image" src="https://github.com/user-attachments/assets/c7c559fa-c8f8-4e89-9140-ae7a81544060" />
<img width="808" height="252" alt="image" src="https://github.com/user-attachments/assets/fcb73651-a20b-41b7-a06c-811774195329" />
<img width="712" height="266" alt="image" src="https://github.com/user-attachments/assets/c477c256-628a-437d-a79f-6da41ec4fb77" />
•	Insertar entre 80 y 150 registros reales en cada tabla. 
Clientes
<img width="483" height="422" alt="image" src="https://github.com/user-attachments/assets/768a3861-ff65-4018-9e75-6b47abaaa9d0" />
<img width="454" height="426" alt="image" src="https://github.com/user-attachments/assets/a0a7006b-081b-40fc-960b-83f34a1be0ed" />
•	Productos
<img width="555" height="461" alt="image" src="https://github.com/user-attachments/assets/55f578b0-945b-4332-8134-5e7b9c554520" />
<img width="543" height="443" alt="image" src="https://github.com/user-attachments/assets/448d6e2e-840d-44ab-b3dd-bd2e6ec15483" />
•	Ventas
<img width="393" height="425" alt="image" src="https://github.com/user-attachments/assets/99c72581-8e2d-4a70-b9d1-7f41db758ccc" />
<img width="371" height="431" alt="image" src="https://github.com/user-attachments/assets/109eb5b0-7f56-4b86-8706-4cae69a9fa4a" />
•	detalle_venta
<img width="513" height="504" alt="image" src="https://github.com/user-attachments/assets/0c73382a-24f5-44bd-96fa-c79ca8ec76a4" />
<img width="409" height="491" alt="image" src="https://github.com/user-attachments/assets/36ca5e35-a91b-4a15-aeb5-9e1ce5d59e9e" />
PROPONER ENUNCIADOS O PROBLEMAS INDICAR Y REALIZAR 
2.	Realizar 5 Consultas SQL Básicas 
Requerimiento: 
Crear y ejecutar estas consultas: 
1.	Consulta con WHERE 
<img width="493" height="202" alt="image" src="https://github.com/user-attachments/assets/c7504483-1c36-472c-96b2-d17fcf159907" />
<img width="320" height="288" alt="image" src="https://github.com/user-attachments/assets/b89dd186-8188-4725-921d-b628c5347867" />
2.	Consulta con LIKE
<img width="448" height="200" alt="image" src="https://github.com/user-attachments/assets/332136c3-a516-44a2-9810-15450a524466" />
<img width="231" height="293" alt="image" src="https://github.com/user-attachments/assets/5b206bdc-537a-4d8a-851d-51068d270274" />
3.	Consulta con ORDER BY
<img width="489" height="133" alt="image" src="https://github.com/user-attachments/assets/d10d6d91-8c97-4e6e-b78a-25aeedc569cd" />
<img width="398" height="257" alt="image" src="https://github.com/user-attachments/assets/3c65f13d-6681-4a06-afd8-67546a04c538" />
4.	Consulta con GROUP BY 
<img width="538" height="155" alt="image" src="https://github.com/user-attachments/assets/a1cbeaea-4cf1-4959-88c8-2f9caaf60bda" />
<img width="356" height="163" alt="image" src="https://github.com/user-attachments/assets/f12b2904-7477-4217-a27c-0c617fbba3a9" />
5.	Consulta con alguna función agregada (SUM, AVG, COUNT, etc.) 
<img width="486" height="120" alt="image" src="https://github.com/user-attachments/assets/26b4173c-f3c2-4b4b-8f9a-052c740ec635" />
<img width="220" height="83" alt="image" src="https://github.com/user-attachments/assets/6ed59cdf-14ed-4f12-9b2a-344fae6d9857" />
3.	Realizar 3 Subconsultas 
Requerimiento: 
Crear una subconsulta de cada tipo: 
1.	Subconsulta en WHERE 
<img width="475" height="166" alt="image" src="https://github.com/user-attachments/assets/1247d6e6-9054-4eb4-b422-f1c38cf3a050" />
<img width="484" height="166" alt="image" src="https://github.com/user-attachments/assets/ef5e63d5-4713-4509-8a7b-69993dba2188" />
2.	Subconsulta en FROM 
<img width="511" height="258" alt="image" src="https://github.com/user-attachments/assets/8842cd0f-4366-4ec3-9926-62b7066a4c48" />
<img width="244" height="261" alt="image" src="https://github.com/user-attachments/assets/95dcb1fc-70ae-4f36-b7d2-6224f8aaab4a" />
3.	Subconsulta anidada con funciones agregadas 
<img width="559" height="151" alt="image" src="https://github.com/user-attachments/assets/21c88ea9-db48-458d-915c-3cf3a10f3d19" />
<img width="679" height="112" alt="image" src="https://github.com/user-attachments/assets/307f4254-f538-4478-a4d4-5d46717a4de1" />
4.	Crear 3 Índices 
Requerimiento: 
Para cada índice deben entregar: 
1.	Crear el índice en una tabla 
2.	Justificar por qué es necesario 
3.	Ejecutar una consulta SIN índice (medir tiempo) 
4.	Ejecutar la misma consulta CON índice (medir tiempo) 
5.	Comparar y explicar la diferencia 
<img width="613" height="347" alt="image" src="https://github.com/user-attachments/assets/0751b9a3-a538-465d-acb7-524dc6d9e126" />
Justificacion:Mejora búsquedas por nombre cuando se usa LIKE 'Texto%'., la búsqueda pasa de un table-scan completo a un index-range-scan.
<img width="382" height="334" alt="image" src="https://github.com/user-attachments/assets/e89eb700-7452-4e14-9da9-104917f93dbf" />
<img width="502" height="291" alt="image" src="https://github.com/user-attachments/assets/d37bb3e6-f768-4094-b158-1186c1f90dac" />
Justificación: Acelera consultas de reportes por fecha.

<img width="496" height="261" alt="image" src="https://github.com/user-attachments/assets/08337624-7775-4958-b9de-34faa9b81abe" />
<img width="459" height="257" alt="image" src="https://github.com/user-attachments/assets/6fcc18ef-01fc-494d-9c55-1e93723b276b" />
Justificación: Útil cuando se obtienen ventas de un producto específico.

5.	Evaluación de Rendimiento con Índices Requerimiento: 
•	Seleccionar 2 consultas lentas 
•	Ejecutarlas SIN índice y registrar tiempo 
•	Crear un índice adecuado 
•	Ejecutar nuevamente y registrar tiempo
•	Escribir una comparación final 
<img width="496" height="175" alt="image" src="https://github.com/user-attachments/assets/f3056b97-109b-4c62-9721-3e59355a6c69" />
<img width="428" height="181" alt="image" src="https://github.com/user-attachments/assets/908de9c8-8fc3-42bd-a314-e6dc8a11fa19" />
El tiempo aumentó ya que puede haberse generado un error por duplicación, como se puede ver antes de crear el índice no hubo tiempo de demora. 

<img width="457" height="159" alt="image" src="https://github.com/user-attachments/assets/a91b6217-8327-4459-9a0e-09c8835e6b3c" />
<img width="414" height="167" alt="image" src="https://github.com/user-attachments/assets/543eb739-5d47-4153-bb53-f4f1ed6a5dcd" />
En este caso sucede lo mismo el cual se puede deber a que la consulta no es tan lenta de ejecutar con o sin indice. 

6.	Crear 3 Vistas 
Requerimiento: 
Para cada vista deben entregar: 
1.	CREATE VIEW 
2.	Consulta que la utiliza 
3.	Explicación del por qué esa vista es útil y en qué escenario se usaría 
<img width="566" height="203" alt="image" src="https://github.com/user-attachments/assets/fb1e547c-459a-4efc-8eca-ff60758c58d6" />
Para reportes rápidos sin escribir JOIN cada vez.

<img width="627" height="165" alt="image" src="https://github.com/user-attachments/assets/bc310dc7-9ad3-4989-9549-8ea465ad020e" />
es útil porque unifica información que normalmente está distribuida en varias tablas (detalle_venta y productos).

<img width="466" height="244" alt="image" src="https://github.com/user-attachments/assets/17ac3e7d-0dda-4ab9-ad50-d19a9c44e032" />
Ayuda a detectar productos que requieren reposición.

7.	Crear 3 Transacciones 
Requerimiento: 
Cada transacción debe incluir: 
•	START TRANSACTION; 
•	Al menos 2 operaciones (INSERT, UPDATE o DELETE) 
•	Un SAVEPOINT 
•	Un ROLLBACK o COMMIT 
•	Ejemplo de salida final 
<img width="795" height="264" alt="image" src="https://github.com/user-attachments/assets/969fd5d1-d4b4-47f0-9275-10304de45c4c" />
<img width="755" height="256" alt="image" src="https://github.com/user-attachments/assets/877a54d1-4efe-447e-be23-ea61a6794679" />
<img width="795" height="227" alt="image" src="https://github.com/user-attachments/assets/a1de1522-d348-4158-908a-ac1734eaaa3c" />

8.	Crear 3 Procedimientos Almacenados 
Requerimiento: 
Cada procedimiento debe incluir: 
•	Parámetros de entrada 
•	Variables internas con DECLARE 
•	Asignaciones usando SET 
•	Alguna consulta o actualización en tablas 
•	Ejecución demostrada con CALL 
<img width="518" height="400" alt="image" src="https://github.com/user-attachments/assets/5c53e5e1-4382-4175-ae1c-1047b7420512" />
<img width="429" height="175" alt="image" src="https://github.com/user-attachments/assets/0ace3446-b8f6-40ca-8a1b-dd6bac644af0" />
<img width="767" height="488" alt="image" src="https://github.com/user-attachments/assets/b81b800c-d7a9-4125-af6f-45f4d9bb2bda" />
<img width="871" height="508" alt="image" src="https://github.com/user-attachments/assets/054f90b0-eba6-4a64-be0a-bb69e66da946" />










