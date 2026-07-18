# Tests.marvel_QA

Un repositorio dedicado a las pruebas (manuales y automatizadas) realizadas en el sitio web oficial de Marvel.
Este repositorio está dedicado a la planificación, ejecución y automatización de pruebas de Quality Assurance (QA) realizadas en el sitio web oficial de [Marvel](https://www.marvel.com).
El objetivo principal es garantizar la calidad, estabilidad y usabilidad de las principales funcionalidades de la plataforma por medio de enfoques manuales y automatizados.

---

## 🚀 Tecnologías y Herramientas Utilizadas

*   **Pruebas Manuales:** planillas de escenarios de prueba e informes, evidencias, plan de ejecución y matriz de trazabilidad.
*   **Automatización:** Robot Framework
*   **Lenguaje:** Python
*   **Gestión:** Git y GitHub.

---

## 📋 Escenarios de Prueba Cubiertos

La automatización cubre los siguientes **3 escenarios** críticos dentro del ecosistema de Marvel:

1.  **Busca personaje:** Validación del sistema de búsqueda principal para localizar héroes y villanos específicos.
2.  **Visualizacion de detalle personaje:** Verificación de la carga correcta de la página de perfil del personaje, asegurando que se muestre su información, biografía y detalles relacionados.
3.  **Consulta/listado de comics:** Comprobación del sistema de listado, carga y filtros al consultar los cómics disponibles en la plataforma.

---

## 🛠️ Cómo Ejecutar las Pruebas Automatizadas

Sigue los pasos a continuación para extraer el proyecto y ejecutar las pruebas en tu máquina a través de **VS Code**:

### 📋 Prerrequisitos

Asegúrate de tener instalado en tu máquina:
*   [Python 3.x](https://www.python.org/)
*   [Visual Studio Code (VS Code)](https://code.visualstudio.com/)
*   Google Chrome (actualizado)

---

### ⚙️ Instalación y Configuración

1. **Extrae el archivo:** Descarga y descomprime el archivo `Marvel_qa.zip` que se encuentra en este repositorio en una carpeta de tu preferencia.
2. **Abre en VS Code:** Abre VS Code, ve al menú superior en `File > Open Folder...` (Archivo > Abrir Carpeta) y selecciona la carpeta que acabas de descomprimir.
3. **Instala las dependencias:** Abre la terminal integrada de VS Code (`Ctrl + '` o `Ctrl + Shift + '`) e instala Robot Framework y SeleniumLibrary ejecutando el comando:
   ```bash
   pip install robotframework robotframework-seleniumlibrary
