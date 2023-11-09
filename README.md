# Práctica 5 I Flask Con Iniciar Sesión 🐈

---

### Información Básica ✨

**Nombre:** Barba Navarro Luis Rodrigo

**Fecha (Creación):** 08/11/23

**Descripción:** En este repositorio, se almacena una aplicación en Flask que posibilita la autenticación de usuarios y la presentación de una página de bienvenida. Durante la elaboración de este proyecto, se ha empleado la técnica de herencia de plantillas vía Jinja y se han implementado los métodos GET y POST.

---

### Recursos ✨

!["Primer Ejemplo"](https://i.imgur.com/ObdCrNm.png)
!["Segundo Ejemplo"](https://i.imgur.com/vqK528A.png)

---

### Implementación ✨

En primer lugar, considero que la organización de los directorios en esta práctica es efectiva, ya que Flask utiliza esta estructura para reconocer la ubicación de los archivos según el nombre de las carpetas, lo que simplifica la gestión.

Respecto a la definición de rutas en Flask, encontré el proceso relativamente sencillo. Una de las novedades en esta práctica fue la posibilidad de que la función de inicio de sesión, a través de la ruta 'login', pueda recibir parámetros del formulario HTML. Luego, procesa estos datos para identificar las solicitudes de tipo POST y verifica la validez de la información ingresada. En caso de éxito, redirige a la página principal ('home'). De lo contrario, se muestra una advertencia si los datos no son correctos. Además, se incorporó un archivo de configuración que permite establecer el modo de desarrollo y depuración, evitando así la necesidad de reiniciar el servidor con cada cambio.

En esta práctica, también destacaría la implementación de la herencia de plantillas utilizando Jinja. Esta técnica facilitó la creación de vistas para las páginas de inicio de sesión y la página principal. La plantilla base contenía elementos compartidos, como una barra de navegación y un pie de página, lo que permitió centrarse en el contenido específico de cada página. En el caso de la página de inicio de sesión, se utilizó una plantilla de Bootstrap y se modificaron los nombres de los campos de texto para que coincidieran con las variables utilizadas en la aplicación, facilitando la recopilación de datos al hacer clic en el botón de inicio de sesión.
