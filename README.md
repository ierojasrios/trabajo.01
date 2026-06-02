#HTML
Lenguaje de marcado de texto, es la parte que nos permite extructurar nuestra pagina web, es como el esqueletode nuestra aplicacion
su principal pbejtuivo es darle formato semantico a nuestra informacion a travez del uso de ´elementos´ que esta a su vez esta conformado por etiquetas de apertura y cierre´contenido´.
        - En algunos casos encontraremos los ´elementos´ huerfano estos solo estan confromados por una sola ´etiqueta´


# 🧱 ¿QUÉ SON LAS ESTRUCTURAS EN HTML?

Las estructuras en HTML son etiquetas que ayudan a organizar el contenido de una página web.  
Cada estructura tiene una función diferente y permite que el navegador entienda cómo está formada la página.

Estas estructuras sirven para:
- Organizar el contenido
- Mejorar la lectura del código
- Facilitar el diseño de páginas web
- Ayudar a los navegadores y buscadores

---

# 🌐 ESTRUCTURAS BÁSICAS DE HTML

## 🔹 `<!DOCTYPE html>`

Es la declaración que indica que el documento utiliza HTML5.

### 📌 Función:
Le dice al navegador qué versión de HTML está usando la página.

### 💻 Ejemplo
```html
<!DOCTYPE html>
```

---

## 🔹 `<html>`

Es la etiqueta principal del documento.

### 📌 Función:
Contiene toda la página web.

### 💻 Ejemplo
```html
<html lang="es">
</html>
```

---

## 🔹 `<head>`

Contiene información de configuración de la página.

### 📌 Función:
Guarda datos importantes que no se muestran directamente en pantalla.

### 💻 Ejemplo
```html
<head>
    <title>Mi Página</title>
</head>
```

---

## 🔹 `<meta>`

Es una etiqueta de configuración.

### 📌 Función:
Permite definir caracteres especiales y adaptar la página a dispositivos móviles.

### 💻 Ejemplo
```html
<meta charset="UTF-8">
```

---

## 🔹 `<title>`

Define el nombre de la página.

### 📌 Función:
Muestra el título en la pestaña del navegador.

### 💻 Ejemplo
```html
<title>Mi Página Web</title>
```

---

## 🔹 `<body>`

Es la parte visible de la página web.

### 📌 Función:
Contiene:
- Textos
- Imágenes
- Botones
- Enlaces
- Formularios

### 💻 Ejemplo
```html
<body>
    <h1>Hola Mundo</h1>
</body>
```

---

# 🧩 ESTRUCTURAS SEMÁNTICAS

Las etiquetas semánticas ayudan a dividir la página en partes organizadas.

---

## 🔹 `<header>`

Representa la cabecera de la página.

### 📌 Función:
Generalmente contiene:
- Logo
- Título
- Menú

### 💻 Ejemplo
```html
<header>
    <h1>Mi Sitio Web</h1>
</header>
```

---

## 🔹 `<nav>`

Representa el menú de navegación.

### 📌 Función:
Permite moverse entre páginas o secciones.

### 💻 Ejemplo
```html
<nav>
    <a href="#">Inicio</a>
</nav>
```

---

## 🔹 `<main>`

Contiene el contenido principal.

### 📌 Función:
Aquí se coloca la información más importante.

### 💻 Ejemplo
```html
<main>
    <p>Contenido principal</p>
</main>
```

---

## 🔹 `<section>`

Divide la página en secciones.

### 📌 Función:
Organiza diferentes temas.

### 💻 Ejemplo
```html
<section>
    <h2>Noticias</h2>
</section>
```

---

## 🔹 `<article>`

Representa contenido independiente.

### 📌 Función:
Se utiliza para:
- Noticias
- Blogs
- Publicaciones

### 💻 Ejemplo
```html
<article>
    <h2>Artículo</h2>
</article>
```

---

## 🔹 `<aside>`

Contiene información secundaria.

### 📌 Función:
Se usa para:
- Publicidad
- Información adicional
- Menús laterales

### 💻 Ejemplo
```html
<aside>
    <p>Publicidad</p>
</aside>
```

---

## 🔹 `<footer>`

Representa el pie de página.

### 📌 Función:
Contiene:
- Derechos de autor
- Redes sociales
- Información de contacto

### 💻 Ejemplo
```html
<footer>
    <p>Derechos reservados</p>
</footer>
```

---

# ✅ RESUMEN GENERAL

| ESTRUCTURA | FUNCIÓN |
|---|---|
| `<!DOCTYPE html>` | Define HTML5 |
| `<html>` | Contiene toda la página |
| `<head>` | Configuración |
| `<meta>` | Caracteres y adaptación |
| `<title>` | Título del navegador |
| `<body>` | Contenido visible |
| `<header>` | Cabecera |
| `<nav>` | Navegación |
| `<main>` | Contenido principal |
| `<section>` | Secciones |
| `<article>` | Artículos |
| `<aside>` | Información extra |
| `<footer>` | Pie de página |

---

# 🚀 CONCLUSIÓN

Las estructuras HTML son fundamentales para crear páginas web organizadas y profesionales.

📘 Gracias a estas etiquetas:
- El código es más ordenado
- La página es más fácil de entender
- Mejora la estructura del sitio web
- Facilita el trabajo del desarrollador
- 

# css (cascadeing stily sheet)
cascade de hojas de estilo, es el dpcumento que nos permite darle estilo a nuestros elementos, posicionar, formato, escalar, color y transcisiones. 
# maneras de aplicar css a nuestro documento html
### 1. en linea
este manera de aplicar css es haciendo uso de los atributos de un elemento en este caso en especial usando el atributo 'style'
'''html
<p style="color:pink;size:23px">este es el texto</p>
'''

### 2. embebidos
este tipo de aplicar estilo nos permite hacer uso de la etiqueta style para poder estilar nuestrs elementos, por convencio esta etiqueta ´style´ al ser de configuracion se debe usar en 
### 3. archivo externo
es la manera correcta y mas usada para aplicar estilo dentro de un documento `html`, para asociar un archivoexterno lo tenemos que hacer en nuestra etequeta de configuracion `head`, haciendo uso de la etiqueta `link` a travez de su atributo ´href´, en este atributo le indicamos la ruta del archhivo que se debe  asociar.