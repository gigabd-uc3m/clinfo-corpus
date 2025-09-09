# clinfo-corpus
La finalidad de este documento es facilitar el mantenimiento conjunto del repositorio GitHub y de la carpeta en Google Drive, hemos definido un estándar común de almacenamiento y nombrado de los corpus y sus metadatos.

**1. Estructura básica**<br>
Cada corpus debe almacenarse en una carpeta independiente. Dentro de esa carpeta habrá siempre:<br>
 I) El fichero de texto con el contenido del corpus.<br>
 II) El fichero README con los metadatos del corpus.<br>
Un ejemplo de cómo quedaría el repositorio sería:<br>
    .<br>
    └── 2024-legal-funcionarios-ocr-boe<br>
            ├── 2024-legal-funcionarios-ocr-boe.txt<br>
            └── README.txt<br>


**2. Nombre de carpeta y ficheros**<br>
El nombre de la carpeta (y del archivo de corpus) seguirá el formato utilizando los siguientes atributos:<br>
[año]-[tema]-[población]-[tipo]-[origen]<br>
<br>
Un ejemplo de cómo quedaría el repositorio sería:<br>
    .<br>
    ├── 2001-social-no_nativos-chat-foro_inmigracion<br>
    ├── 2005-educacion-estudiantes-paralelo-webapp<br>
    ├── 2024-legal-funcionarios-ocr-boe<br>
    │         ├── 2024-legal-funcionarios-ocr-boe.txt<br>
    │         └── README.txt<br>
    └── 2025-salud-adultos_mayores-monolingue-ministerio<br>
              ├── 2025-salud-adultos_mayores-monolingue-ministerio.txt<br>
              └── README.txt<br>
<br>

<br>
**3. Fichero de metadatos (README.txt)**<br>
<br>
Dentro de cada carpeta se incluirá siempre un README.txt en texto plano. La idea es que este archivo documente los metadatos esenciales para facilitar el registro, seguimiento y reutilización del corpus.<br>
Los campos obligatorios son:<br>
    **1º) Origen** – Fuente o procedencia del corpus.<br>
    **2º) Descripción** – Breve explicación del contenido o propósito.<br>
    **3º) Tema** – Área temática principal.<br>
    **4º) Población** – Público objetivo.<br>
    **5º) Tipo** – Naturaleza o formato del corpus.<br>
    **6º) Creación** – Fecha y método de creación/recolección.<br>
    **7º) Validado** – Método de validación de calidad (manual, automático o mixto).<br>
<br>
Un ejemplo de un fichero de metadatos sería:<br>
    _Origen: Web scraping de páginas de la administración pública (sitio X)<br>
    Descripción: Comunicados oficiales simplificados durante una campaña de salud pública.<br>
    Tema: Salud<br>
    Población: Ciudadanos generales<br>
    Tipo: Monolingüe texto plano<br>
    Creación: 2025-06-12 – Web scraping con script Python (BeautifulSoup)<br>
    Validado: Mixto – validación automática y comprobación manual de 200 muestras_<br>
<br>
<br>
**4. Ubicación**<br>
Este formato de estructuras y nomenclatura se debe seguir tanto en el repositorio de GitHub como en el de Google Drive. Es decir, cuando se cree la carpeta y se suban los ficheros correspondientes a un corpus, **se deben subir tanto al Drive como al GitHub.**<br>
<br>
