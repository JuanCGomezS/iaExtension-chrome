## **Prerrequisitos**
Antes de comenzar a usar la Extensión AI para Chrome, asegúrate de tener lo siguiente:
* Clona este repositorio en tu máquina local o descarga el código fuente como un archivo ZIP.
* Abre Google Chrome y ve a chrome://extensions.
* Activa el interruptor de "Modo desarrollador" en la esquina superior derecha.
* Haz clic en el botón "Cargar sin empaquetar" y selecciona el directorio donde clonaste o extrajiste los archivos de la extensión.
* La Extensión AI para Chrome se instalará y estará lista para usar.

<br>

## **Configuración**
Después de instalar la extensión, necesitas obtener una clave API de OpenAI. Sigue estos pasos para configurar la extensión:
Visita el sitio web de OpenAI en https://openai.com/ y crea una cuenta si aún no lo has hecho.
Una vez que tengas una cuenta, navega a la sección de gestión de claves API.
Genera una nueva clave API para tu aplicación o proyecto.
Configura la extensión con tu clave API:
Abre el archivo popup.js en un editor de código de tu elección y navega a la línea 121.

Copia el siguiente fragmento de código y reemplaza la línea 121 existente con él:

```bash
request.setRequestHeader("Authorization", "Bearer <!--YOUR-API-KEY-->");
Reemplaza <YOUR-API-KEY> con la clave API que obtuviste de OpenAI.
Guarda los cambios.
```

<br>

## **Uso**
Una vez que la extensión esté instalada, configurada y la clave API esté lista, podrás disfrutar de sus potentes funciones:

<br>
* Modo Predeterminado: Simplemente escribe tus preguntas o consultas en la interfaz de la extensión, y el asistente AI proporcionará respuestas e información útil.
* Modo Resumen: Para resumir un texto, pégalo en la interfaz de la extensión o escríbelo directamente. El asistente AI generará un resumen conciso del contenido.
* Modo Corrección Gramatical: Si deseas revisar y corregir la gramática de un texto, ya sea un correo electrónico, una publicación de blog o cualquier otro contenido escrito, pégalo en la interfaz de la extensión. El asistente AI analizará el texto y sugerirá mejoras en gramática y legibilidad.

Notas: Usa la sección "Notas" para escribir recordatorios, información importante o notas personales.
Ten cuidado al pegar información sensible, ya que se almacenará en el almacenamiento de la aplicación.

Temas: Accede al menú "Temas" para seleccionar tu tema preferido. Elige entre una selección de cuatro temas, y el tema seleccionado se guardará en el almacenamiento local.

<br>
Siente la libertad de cambiar entre los modos según tus necesidades y explora todas las capacidades de la Extensión AI para Chrome.

<br>
Contribuciones
¡Las contribuciones siempre son bienvenidas! Si tienes ideas, sugerencias o informes de errores, abre un problema o envía una solicitud de extracción para contribuir al desarrollo de la Extensión AI para Chrome.

<br>
Licencia
La Extensión AI para Chrome está licenciada bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.