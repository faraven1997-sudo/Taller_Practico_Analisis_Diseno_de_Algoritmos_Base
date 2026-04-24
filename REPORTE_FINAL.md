# Taller_Practico_Analisis_Diseno_de_Algoritmos_Base
solucion de tipo bitacora en enfasis a los aplicativos pseint y flowgorithm
PARTE 1
# Actividad 1: Búsqueda Binaria
Ejecuta el programa (botón ▶)
Ingresa: 3301
Salida esperada:
Comparando con posición 3: 3301 
✓ ¡ÉXITO! Registro localizado 
Posición en el sistema: 3 
Valor del registro: 3301
# Ejemplo de exito en la operacion
se puede evidenciar que dentro del algoritmo este contempla varias variables antes de dar con el numero o valor buscado, de esta forma este proceso puede pasar
por cada fila de manera casi ilimitada hasta dar con la busqueda este proceso pasa en milisegundos no obstante solo aplicaria para elemtendp existete dentro
del algoritmo, como lo fue en este caso.
<img width="1279" height="718" alt="Test Case 1 (Caso Éxito)" src="https://github.com/user-attachments/assets/d9c2a7f3-09ee-4948-8be5-9548a410b503" />

# Ejemplo de error en la operacion
en este caso el caso no fue exitoso pues al ingresar un numero no existente en el programa este presenta un error, y por lo mismo la busqueda se detiene 
para ello el sistema solo va a reconocer a la in formacion agregada dentro de los parametros de la variable.
<img width="1279" height="718" alt="Test Case 1 (Caso Éxito)" src="https://github.com/user-attachments/assets/29091552-0a34-4932-8037-58067857da2b" />

# Complejidad: O(log n)
Métrica	Valor
¿Cuántas comparaciones se hacen al buscar 6081 en ambos algoritmos?
# lineal
Tamaño del arreglo (n)	7
Iteraciones máximas esperadas	ceil(log₂ 8) = 8
Iteraciones reales (32)
Complejidad Big O	O(log n)
Comparaciones vs búsqueda lineal	Binaria: ~3 vs Lineal: ~8

# Actividad 2: Análisis con Flowgorithm
En el diagrama podemos visulalizar una estructura visual menos compleja pero mas entendible, en este diagrama podemos validar los diferentes flujos
en un esquema conceptual, casi como pseint pero con un orden mas establecido y propenso a errores, no obstante con este es mas facil visuaalizar una estrcutura
antes de emplearla en pseint o en cualquier otro programa, es decir, en un acercamiento a una estructura base que no requiere terminos complejos pero si una
logica avanzada para su funcionamiento.
# ejemplo estructura 
<img width="418" height="557" alt="Actividad 2 Análisis de Complejidad con Flowgorithm" src="https://github.com/user-attachments/assets/a8a0baf4-f245-4a1d-b92c-e2e1217684a3" />

# Actividad 3: Colas FIFO
confirmacion cola de fifo
Paso	Operación	Entrada	Cola Resultante	Tamaño	Verificación
1	Enqueue	"A"	[A]	1	✓
2	Enqueue	"B"	[A, B]	2	✓
3	Enqueue	"C"	[A, B, C]	3	✓
4	Dequeue	-	[B, C]	2	✓ (Salió A)
5	Dequeue	-	[C]	1	✓ (Salió B)
<img width="1279" height="719" alt="Simulador FIFA" src="https://github.com/user-attachments/assets/e3edb4d2-bf1b-41ce-863e-19228aea2220" />
de este proceso se puede entender que cada entrada tiene una probabilidad de aparacer segun el criterio de busqueda, no obstante como en todo complejo proceso
si se ingresa una opcion o valor invalido este lanzara un error y se dejara de ejecutar.

# Actividad 4: Comparativa
si es falso se presentara el siguiente escenario
<img width="1279" height="718" alt="Falso" src="https://github.com/user-attachments/assets/d3881e0c-376e-49f7-aff8-45ea98a27c95" />

si es verdadero se presentara el siguiente escenario
<img width="1279" height="720" alt="verdadero" src="https://github.com/user-attachments/assets/7211b7bf-0ed7-426d-8b23-016ace12e923" />

# declaracion
La mejora se amplifica exponencialmente con datasets más grandes, cuando el algoritmo tiene mas informacion este se vuelve mas complejo pero la informacion es mas
amplia, pero se pueden presentar otros errores, recomendacion aplicar la misma estructura para cada nueva indormacion sin modificar los codigos.

# Conclusiones y Aprendizajes

Segun cada proceso empleado y ejecutado cada variable y estructura tiene sus pros y sus contras, cada una debe aplicarse para casos concrentos, la busqueda lineal
es perfecta para infomacion ordenada pero la binaria es mejor para informacion mucho mas amplia, ademas, si empleamos los esquemas de flowgorithm podemos tener
una previa de como se veria nuestro algoritmos antes de estructurarlo en pseint u otros programas, entender que cada proceso y cada formula se puede utilizar para 
diferentes operaciones pero mezclarlas puede ser contraproducente pues cada una consta de una funcion concreta, entender esta parte es fundamental pues entre 
cada mezcla de codigos resulta en un proceso y dicho proceso cumple con una funcion segun el proposito.
