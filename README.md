# clinfo-corpus
La finalidad de este documento es facilitar el mantenimiento conjunto del repositorio GitHub y de la carpeta en Google Drive, hemos definido un estándar común de almacenamiento y nombrado de los corpus y sus metadatos.

**1. Estructura básica**
Cada corpus debe almacenarse en una carpeta independiente. Dentro de esa carpeta habrá siempre:
 I) El fichero de texto con el contenido del corpus.
 II) El fichero README con los metadatos del corpus.
Un ejemplo de cómo quedaría el repositorio sería:
  .
  └── 2024-legal-funcionarios-ocr-boe
            ├── 2024-legal-funcionarios-ocr-boe.txt
            └── README.txt


**2. Nombre de carpeta y ficheros**
El nombre de la carpeta (y del archivo de corpus) seguirá el formato utilizando los siguientes atributos:
[año]-[tema]-[población]-[tipo]-[origen]
Un ejemplo de cómo quedaría el repositorio sería:
  .
  ├── 2001-social-no_nativos-chat-foro_inmigracion
  ├── 2005-educacion-estudiantes-paralelo-webapp
  ├── 2024-legal-funcionarios-ocr-boe
  │         ├── 2024-legal-funcionarios-ocr-boe.txt
  │         └── README.txt
  └── 2025-salud-adultos_mayores-monolingue-ministerio
             ├── 2025-salud-adultos_mayores-monolingue-ministerio.txt
             └── README.txt


**3. Fichero de metadatos (README.txt)**
Dentro de cada carpeta se incluirá siempre un README.txt en texto plano. La idea es que este archivo documente los metadatos esenciales para facilitar el registro, seguimiento y reutilización del corpus.
Los campos obligatorios son:
  **1º) Origen** – Fuente o procedencia del corpus.
  **2º) Descripción** – Breve explicación del contenido o propósito.
  **3º) Tema** – Área temática principal.
  **4º) Población** – Público objetivo.
  **5º) Tipo** – Naturaleza o formato del corpus.
  **6º) Creación** – Fecha y método de creación/recolección.
  **7º) Validado** – Método de validación de calidad (manual, automático o mixto).

Un ejemplo de un fichero de metadatos sería:
  _Origen: Web scraping de páginas de la administración pública (sitio X)
  Descripción: Comunicados oficiales simplificados durante una campaña de salud pública.
  Tema: Salud
  Población: Ciudadanos generales
  Tipo: Monolingüe texto plano
  Creación: 2025-06-12 – Web scraping con script Python (BeautifulSoup)
  Validado: Mixto – validación automática y comprobación manual de 200 muestras_


**4. Ubicación**
Este formato de estructuras y nomenclatura se debe seguir tanto en el repositorio de GitHub como en el de Google Drive. Es decir, cuando se cree la carpeta y se suban los ficheros correspondientes a un corpus, **se deben subir tanto al Drive como al GitHub.**

