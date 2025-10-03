<h1 align="center"><img height="40" src="https://github.com/Aquiles369/iconos/blob/main/img/lobo1.gif"><img height="40" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWx4YTl1dW9scXlqZDk2cTdyY2VvcXQwMG40OGoxY25rZzV0MDZhcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/peSyJWjNTRfzaWh49M/giphy.gif">"Repositorio-de-Payloads"<img height="40" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWx4YTl1dW9scXlqZDk2cTdyY2VvcXQwMG40OGoxY25rZzV0MDZhcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/peSyJWjNTRfzaWh49M/giphy.gif"><img height="35" src="https://github.com/Aquiles369/iconos/blob/main/img/lobo1.gif"> </h1>	


<br>


<p align="center">
 <img  height="470rem" alt="GIF" src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExcHlvMWZuMHA2cGp3dHQzeW16NGxncHdhNzc4bTkyMWNqdHB6NXZxaCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/S3u9jpaBahRAugXHuE/giphy.gif"/>
</p>

<picture> <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">  </picture>

 ### <picture> <img src = "https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2VscGV1NWIzZG81aTV1Yjhmd3V2OHA1cXlneHNsMmk0dWFjcGg5MSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9dHM/Dv8Klv7asiQFXRjSp9/giphy.gif" width = 75px>  </picture> Gestor de cargas útiles

<br>

 **Repositorio de Payloads — gestor offline con filtros y notas. Una tool offline para gestionar payloads de bug bounty.
Permite crear categorías personalizadas (XSS, IDOR, RCE, etc.), agregar renglones con payloads, asignarles un estado (muy bueno, bueno, medio, débil), añadir notas con tooltip, copiar ítems o listas completas y buscar en todo el repositorio. Todo queda guardado en localStorage, con funciones para exportar/importar JSON y borrar todo.,<a href="https://youtu.be/-xbUK4-LGUw" target="_blank" rel="noopener">demo de la tool Youtube</a>.** 
<br><br> 

<p align="center">
 <img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/iconos/blob/main/demo_colab.gif"/>
</p>

<br>

<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExMTluamxsZ29hbTV2Zmw0OWNwN2cxMHI4azl1YTBvemYybW80eHRlZiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/hvSd2YvTdBlniSJ8tA/giphy.gif" width = 80px>  </picture> Resumen rápido
<br><br>

Tool offline en el navegador para gestionar payloads de bug bounty. Sin instalar nada: abrís el HTML y ya podés crear, editar o eliminar categorías, agregar renglones con payloads, asignar estados (muy bueno/bueno/medio/débil), filtrar, anotar y copiar. Todo queda guardado en localStorage; también podés exportar/importar JSON o resetear.<br>


• Formato: interfaz web local (HTML/JS), toda la data se guarda en localStorage por defecto (offline, en tu máquina).<br><br>


<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExeWVleDk0Y3lmdmN1eWU3eWowNGsyaGlpbHQwbTM0aDNia21qbjNpayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/S3caeWZviAaDtzmU7X/giphy.gif" width = 80px>  </picture> Características
<br><br>

Categorías dinámicas:

• Crear, renombrar y eliminar categorías.

• Cada categoría muestra la cantidad de payloads que contiene.

• Cada categoría trae su filtro propio: todos, sin etiqueta, muy bueno, bueno, medio, débil. <br>

Gestión de payloads (renglones):
Cada renglón tiene:<br>

• Título editable (Nuevo payload por defecto).

• Campo de texto para payload.

• Botón Copiar al portapapeles.

• Píldora de estado (muy bueno / bueno / medio / débil / sin etiqueta).

• Notas: modal para editar y guardar; tooltip flotante con preview y fecha de última edición; indicador rojo si existe nota.

• Botón Borrar para eliminar el payload.<br>


Funciones por categoría

• Agregar renglón.

• Copiar TODOS los payloads de la categoría (respeta el filtro activo

• Eliminar categoría completa.<br>

Buscador global

• Panel lateral fijo.

• Filtra por título, payload, nota o categoría.

• Resalta y lleva al payload con scroll suave.<br>


Botonera de control (fija en pantalla)

• + Agregar categoría.

• Exportar JSON (copiar base al portapapeles).

• Importar JSON (pegar desde clipboard).

• Borrar todo (reset total).<br>

Persistencia local

• Todo se guarda automáticamente en localStorage.

• Funciona 100% offline, sin servidor ni backend.<br>


Interfaz visual

• Fondo oscuro con gradientes.

• Tarjetas y secciones con glassmorphism (bordes, sombras, blur).<br>


Estados representados por colores claros:

• Verde = Muy bueno

• Azul = Bueno

• Naranja = Medio

• Gris = Débil

<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExenRleDh2cXF1aG9mcjJnank0MzRoNHZoZDFiZ2Y2ZTE0eWdxeGhsbyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/jtvED7ZmtCVyE3xzC2/giphy.gif" width = 80px>  </picture> Uso
<br><br>


1. Abrí el archivo .html en tu navegador.

2. Clic en + Agregar categoría y empezá a crear/renombrar/eliminar.

3. Dentro de cada categoría: Agregar renglón → escribir payload → asignar estado.

4. Usá el filtro por estado o el buscador global para encontrar todo al toque.

5. Opcional: Notas (tooltip + última edición), Copiar ítem o Copiar TODOS de la categoría.

6. Cualquiera puede usarla: es simple, rápida y todo queda local.


 <br>

<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExc3YwbG9zbmU1amprdTJsbmxzYnpobzd5eGtnazB6b2FmdnllaTRhZyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/h8UlsEpqiCISTKUzvz/giphy.gif" width = 80px>  </picture> "BugBounty HQ: busca, organiza y comparte informes rápido y offline — tu tablero sin dramas."
<br>


<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
