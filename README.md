📘 Manual Técnico
📌 Descripción del proyecto

Este proyecto consiste en una calculadora básica diseñada para realizar operaciones aritméticas sencillas como suma, resta, multiplicación, división, cálculo de porcentaje y raíz cuadrada. El objetivo principal de esta calculadora es proporcionar una interfaz simple e intuitiva para realizar cálculos rápidos, usando la librería Flet para construir interfaces de usuario interactivas.

🖥️ Tecnologías usadas

Python 3.12.10

Flet.

⚙️ Requisitos técnicos

Tener instalado Python 3.10 o superior.

Instalar las dependencias ejecutando el siguiente comando:

pip install flet

<img width="648" height="186" alt="image" src="https://github.com/user-attachments/assets/6df4b5ac-1c45-4330-ba73-58743ecaec0c" />

🧩 Explicación del código

El código está hecho para que el usuario ingrese dos números y realice una serie de operaciones matemáticas.

Funciones principales:

suma(): Realiza la suma de los dos números ingresados.

resta(): Realiza la resta de los dos números.

multiplicacion(): Realiza la multiplicación.

division(): Realiza la división, con manejo de errores para evitar divisiones por cero.

porcentaje(): Calcula el porcentaje de un número basado en otro.

raiz_cuadrada(): Calcula la raíz cuadrada de ambos números.

🛠️ Posibles errores y soluciones

División por cero: Si el segundo número es 0 y se intenta realizar una división, la calculadora mostrará "División por cero". Solución: Evitar ingresar 0 como segundo número en una división.

Entradas no numéricas: Si el usuario ingresa texto o un valor no numérico en los campos de entrada, la calculadora mostrará "Error". Solución: Ingresar solo números válidos.

Error al calcular porcentaje: Si alguno de los números no es válido, se mostrará "Error". Solución: Asegurarse de que ambos campos contengan valores numéricos.

🚀 Cómo ejecutar

Navega a la carpeta del proyecto.

Ejecuta el siguiente comando:

flet run src/main.py


La calculadora se abrirá en un navegador web.


👤 Manual de Usuario
🎯 Presentación de la aplicación

La Calculadora Básica es una herramienta sencilla que permite realizar operaciones matemáticas comunes como:

- Suma

- Resta

- Multiplicación

- División

- Cálculo de porcentaje

- Raíz cuadrada de dos números

🖥️ Requisitos de uso

Tener instalado Python 3.10 o superior.

Instalar la librería Flet con el siguiente comando:

pip install flet

▶️ Pasos para ejecutar

Descargar o clonar el proyecto desde GitHub.

Abrir la terminal en la carpeta del proyecto.

Ejecutar el siguiente comando para lanzar la calculadora:

flet run src/main.py


La aplicación se abrirá en tu navegador.

🔢 Instrucciones de uso

Escribir el primer número en el campo correspondiente.

Escribir el segundo número en el segundo campo.

Presionar el botón de la operación deseada (suma, resta, multiplicación, división, etc.).

Ver el resultado en la sección de resultado, que se actualizará automáticamente.

📸 Ejemplo:

<img width="1357" height="649" alt="calculadora3" src="https://github.com/user-attachments/assets/9d8811ac-4945-4e5c-9206-e90e8380059d" />
<img width="1355" height="648" alt="calculadora1" src="https://github.com/user-attachments/assets/c50c884c-aef6-4e9d-b6ba-7bfb4f7fbf27" />
<img width="1357" height="650" alt="calculadora2" src="https://github.com/user-attachments/assets/812a0b3b-8857-48ea-ba96-c6ec865c52f7" />


❌ Errores comunes

División entre cero: Si intentas dividir entre cero, se mostrará un mensaje de error indicando "División por cero". Asegúrate de no ingresar 0 como el segundo número en una operación de división.

Entradas inválidas: Si se ingresa texto en lugar de números, aparecerá el mensaje "Error". Asegúrate de que ambos campos contengan solo números válidos.
