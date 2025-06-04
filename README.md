# Geometric-Calcweb
Calculadora web simple para área de figuras geométricas, ángulos de triángulos, circunferencias y gráficas trigonométricas. Desarrollada para fines académicos en ESPE – Ecuador.

## ✨ Funcionalidades

- 📐 Cálculo del área de figuras geométricas (triángulo, cuadrado, rectángulo, círculo, etc.).
- 📏 Cálculo de ángulos en un triángulo dados ciertos datos.
- 🔵 Cálculo de propiedades de una circunferencia.
- 📊 Gráficas de identidades trigonométricas.

## 🌐 Tecnologías utilizadas

- HTML5  
- CSS3  
- JavaScript

## 🚀 Cómo usar Geometric-Calcweb

Puedes ejecutar esta aplicación de forma muy sencilla en tu navegador siguiendo estos pasos:

**Paso 1: Ejecutar localmente**

1. **Descarga o clona** este repositorio:
   ```bash
   git clone https://github.com/ItsAlex678/Geometric-Calcweb.git
2. Abre el archivo Trigonometric-CalcWeb.html con doble clic o arrástralo a tu navegador.
3. La calculadora se abrirá en tu navegador con una interfaz amigable y organizada por secciones.

**Paso 2: Usar cada funcionalidad**

## 📐 Área de Figura Geométrica
En la sección Área de Figura Geométrica, selecciona una figura del menú desplegable:

- Cuadrado
- Rectángulo
- Triángulo
- Círculo

Dependiendo de la figura seleccionada, ingresa los datos requeridos:

- Cuadrado: lado
- Rectángulo: base y altura
- Triángulo: base y altura
- Círculo: radio

**Haz clic en "Calcular Área".**

El resultado aparecerá debajo, junto con una explicación del proceso:

- Fórmula utilizada
- Valores ingresados
- Cálculo paso a paso
- Resultado final en cm²

## 📏 Ángulos de un Triángulo
Ve a la sección Ángulos de un Triángulo.
Ingresa los valores de los tres lados del triángulo: a, b y c.
Haz clic en "Calcular Ángulos".

Se mostrará:
- Verificación de si los lados forman un triángulo válido.
- Cálculo del ángulo A usando la ley de los cosenos:

`cos(A) = (b² + c² - a²) / (2bc)
A = arccos(...)` 

Cálculo del ángulo B de forma similar.
Ángulo C calculado con: C = 180° - A - B

*Resultado final con los tres ángulos redondeados en grados.*

## 🔵 Cálculo de Circunferencia

Ve a la sección Cálculo de Circunferencia.
Ingresa el radio de la circunferencia en centímetros.
Haz clic en "Calcular Área y Perímetro".
Aparecerá un resultado con explicación detallada:

- Fórmula del área: Área = π × radio²
- Fórmula del perímetro: Perímetro = 2 × π × radio

*Sustitución de valores y resultado final en cm² y cm.*

## 📊 Gráfica de Identidades Trigonométricas

En la parte inferior encontrarás la sección Gráfica de Identidades Trigonométricas.
El sistema grafica automáticamente las siguientes funciones:

- sen(x)
- cos(x)
- tan(x)

sen²(x) + cos²(x) (identidad trigonométrica)

Puedes pasar el cursor sobre las curvas para ver los valores aproximados de cada función.
El eje x está en radianes desde 0 hasta 2π, y el eje y representa los valores de las funciones.

## 💡 Recomendación
Para una mejor experiencia interactiva, puedes usar la extensión Live Server en Visual Studio Code:

1. Abre la carpeta del proyecto en VSCode.
2. Haz clic derecho sobre el archivo Trigonometric-CalcWeb.html.
3. Selecciona "Open with Live Server".

Esto abrirá la calculadora en tu navegador con recarga automática si haces cambios.
