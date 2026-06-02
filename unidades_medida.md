🎨 Unidades de Medida en Diseño Web y CSS

Las unidades de medida sirven para definir el tamaño de textos, imágenes, márgenes, contenedores y otros elementos en una página web.

📏 1. Unidades Absolutas

Son medidas fijas.
No cambian según la pantalla.

Unidad	Significado	Uso
px	Píxeles	Diseño web
cm	Centímetros	Impresión
mm	Milímetros	Documentos
in	Pulgadas	Impresoras
pt	Puntos	Tipografía
pc	Picas	Diseño editorial
✨ Ejemplo
h1{
   font-size: 40px;
}

📌 El texto tendrá 40 píxeles.

🌐 2. Unidades Relativas

Se adaptan al tamaño de pantalla o del elemento padre.

Unidad	Función
%	Porcentaje
em	Tamaño relativo al padre
rem	Tamaño relativo al HTML
vw	Ancho de pantalla
vh	Alto de pantalla
vmin	Valor menor de pantalla
vmax	Valor mayor de pantalla
📊 3. Unidades Más Usadas
🔹 px

Muy usada para tamaños exactos.

width: 300px;
🔹 %

Responsive y adaptable.

width: 80%;

📌 Ocupa el 80% del contenedor.

🔹 rem

Ideal para textos modernos.

font-size: 2rem;
🔹 vw y vh

Perfectas para pantallas completas.

height: 100vh;
width: 100vw;

📌 Ocupa toda la pantalla.

🎯 4. Unidades Modernas
Unidad	Uso
fr	Dividir espacio en Grid
ch	Tamaño por caracteres
ex	Altura letra x
lh	Altura de línea
clamp()	Responsive avanzado
🧩 Ejemplo con Grid (fr)
grid-template-columns: 1fr 1fr;

📌 Divide el espacio en dos columnas iguales.

📱 Responsive Design
✨ clamp()

Permite tamaños mínimos y máximos automáticos.

font-size: clamp(1rem, 5vw, 3rem);

📌 El texto se adapta según la pantalla.

⏱️ Unidades de Tiempo
Unidad	Significado
s	Segundos
ms	Milisegundos
transition: 2s;
🔄 Unidades de Rotación
Unidad	Función
deg	Grados
rad	Radianes
turn	Vueltas
transform: rotate(45deg);
🖥️ Ejemplo Completo
<div style="
width:80%;
height:100vh;
font-size:clamp(1rem,3vw,2rem);
background:#4F46E5;
color:white;
padding:20px;
">
 Diseño Web Responsive
</div>
⭐ Las Más Importantes en Diseño Web
Unidad	Recomendación
px	Tamaños exactos
%	Responsive
rem	Textos
vw/vh	Pantallas
fr	Grid
clamp()	Diseño moderno