# buscador-genes-ncbi
# 🧬 Buscador Automático de Genes y Proteínas (NCBI)

Este es un script de Python diseñado para facilitar la extracción masiva de datos biológicos desde las bases de datos del **NCBI** (Gene y Protein). Permite introducir múltiples identificadores y genera un informe detallado en formato Excel.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TU_USUARIO/TU_REPO/blob/main/Buscador_Automático_de_Genes.ipynb)

## ✨ Características
* **Búsqueda Flexible:** Acepta nombres de genes (ej. `BRCA1`), nombres de proteínas (`p53`), IDs numéricos de NCBI (`672`) y Accessions (`NP_009225.1`).
* **Automatización:** Clasifica automáticamente el tipo de entrada y busca en la base de datos correspondiente.
* **Salida Profesional:** Genera un archivo `.xlsx` con hojas separadas para Genes y Proteínas, incluyendo enlaces directos a NCBI.
* **Datos Extraídos:** Símbolos oficiales, alias, localización cromosómica, exones, peso molecular, localización subcelular y más.

## 🚀 Cómo usarlo
1. **En Google Colab:** Haz clic en el botón de arriba "Open In Colab", pega tus genes y ejecuta las celdas.
2. **En Local:**
   - Clona el repositorio: `git clone https://github.com/TU_USUARIO/TU_REPO.git`
   - Instala las dependencias: `pip install -r requirements.txt`
   - Ejecuta el script: `python buscador_genes.py`

## 📦 Dependencias
Este proyecto utiliza las siguientes librerías:
* `requests`: Para consultas a la API E-Utils de NCBI.
* `pandas`: Procesamiento de datos.
* `openpyxl`: Generación de reportes Excel con formato.
* `re`: Procesamiento de identificadores mediante expresiones regulares.

## 🛠️ Autor
**Francisco Armando Sánchez Díaz** *Matrícula: 202355940* Desarrollado con fines académicos y de uso libre para la comunidad científica.

## ⚖️ Licencia
Este proyecto es de **uso libre**. Puedes modificarlo, distribuirlo y usarlo como mejor te sirva para tus investigaciones.
