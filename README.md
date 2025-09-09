# clinfo-corpus
La finalidad de este documento es facilitar el mantenimiento conjunto del repositorio GitHub y de la carpeta en Google Drive, hemos definido un estándar común de almacenamiento y nombrado de los corpus y sus metadatos.

**1. Estructura básica**<br>
Cada corpus debe almacenarse en una carpeta independiente. Dentro de esa carpeta habrá siempre:<br>
 I) El fichero de texto con el contenido del corpus.<br>
 II) El fichero README con los metadatos del corpus.<br>
Un ejemplo de cómo quedaría el repositorio sería:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.<br>
&nbsp;&nbsp;&nbsp;&nbsp;└── 2024-legal-funcionarios-ocr-boe<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├── 2024-legal-funcionarios-ocr-boe.txt<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── README.txt<br>


**2. Nombre de carpeta y ficheros**<br>
El nombre de la carpeta (y del archivo de corpus) seguirá el formato utilizando los siguientes atributos:<br>
[año]-[tema]-[población]-[tipo]-[origen]<br>
<br>
Un ejemplo de cómo quedaría el repositorio sería:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.<br>
&nbsp;&nbsp;&nbsp;&nbsp;├── 2001-social-no_nativos-chat-foro_inmigracion<br>
&nbsp;&nbsp;&nbsp;&nbsp;├── 2005-educacion-estudiantes-paralelo-webapp<br>
&nbsp;&nbsp;&nbsp;&nbsp;├── 2024-legal-funcionarios-ocr-boe<br>
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ├── 2024-legal-funcionarios-ocr-boe.txt<br>
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; └── README.txt<br>
&nbsp;&nbsp;&nbsp;&nbsp;└── 2025-salud-adultos_mayores-monolingue-ministerio<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  ├── 2025-salud-adultos_mayores-monolingue-ministerio.txt<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  └── README.txt<br>
<br>

**3. Fichero de metadatos (README.txt)**  
Dentro de cada carpeta se incluirá siempre un README.txt en texto plano. La idea es que este archivo documente los metadatos esenciales para facilitar el registro, seguimiento y reutilización del corpus.<br>
Los campos obligatorios son:<br>
&nbsp;&nbsp;&nbsp;&nbsp;**1º) Origen** – Fuente o procedencia del corpus.<br>
&nbsp;&nbsp;&nbsp;&nbsp;**2º) Descripción** – Breve explicación del contenido o propósito.<br>
&nbsp;&nbsp;&nbsp;&nbsp;**3º) Tema** – Área temática principal.<br>
&nbsp;&nbsp;&nbsp;&nbsp;**4º) Población** – Público objetivo.<br>
&nbsp;&nbsp;&nbsp;&nbsp;**5º) Tipo** – Naturaleza o formato del corpus.<br>
&nbsp;&nbsp;&nbsp;&nbsp;**6º) Creación** – Fecha y método de creación/recolección.<br>
&nbsp;&nbsp;&nbsp;&nbsp;**7º) Validado** – Método de validación de calidad (manual, automático o mixto).<br>
<br>
Un ejemplo de un fichero de metadatos sería:<br>
&nbsp;&nbsp;&nbsp;&nbsp;_Origen: Web scraping de páginas de la administración pública (sitio X)<br>
&nbsp;&nbsp;&nbsp;&nbsp;Descripción: Comunicados oficiales simplificados durante una campaña de salud pública.<br>
&nbsp;&nbsp;&nbsp;&nbsp;Tema: Salud<br>
&nbsp;&nbsp;&nbsp;&nbsp;Población: Ciudadanos generales<br>
&nbsp;&nbsp;&nbsp;&nbsp;Tipo: Monolingüe texto plano<br>
&nbsp;&nbsp;&nbsp;&nbsp;Creación: 2025-06-12 – Web scraping con script Python (BeautifulSoup)<br>
&nbsp;&nbsp;&nbsp;&nbsp;Validado: Mixto – validación automática y comprobación manual de 200 muestras_<br>
<br>
<br>
**4. Ubicación**<br>
Este formato de estructuras y nomenclatura se debe seguir tanto en el repositorio de GitHub como en el de Google Drive. Es decir, cuando se cree la carpeta y se suban los ficheros correspondientes a un corpus, **se deben subir tanto al Drive como al GitHub.**<br>
<br>
