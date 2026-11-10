# Trabajo Bebidas del Maipo S.A.

**Autoras:** Maytte Almuna, Macarena Campos, Darlyn Jerez y Valentina Roa
En este repositorio se podrán encontrar las entregas establecidas, al igual que el trabajo previo de cada entrega

## 🚀 Guía de Uso y Ejecución del Código

Actualmente el proyecto cuenta con la **Entrega 1** (fase previa) y la **Entrega 2** (fase actual de optimización). Para poder visualizar e interactuar con el código, por favor sigue estos pasos:

1. Dirígete a la carpeta llamada **`Codigo`** en el directorio principal.
2. Ingresa a la sección correspondiente a la entrega que deseas evaluar (para la fase actual, selecciona el archivo con el nombre de **`CasodeEstudioE2`**.
3. Haz clic en el botón **"Open in Colab"** que aparece en pantalla. Esto abrirá el entorno de Google Colab en una pestaña nueva.
4. Una vez dentro de Google Colab, asegúrate de **hacer correr cada uno de los bloques de código** de manera secuencial (desde el primero hasta el último).
5. Podrás observar el resultado de los modelos, los cálculos y los cuadros de mando en la parte de más abajo de cada bloque de código ejecutado.

## 📥 Ejecución Local o en Otros Entornos

En caso de que desees clonar este repositorio para reproducir nuestro código en tu propio computador (usando Jupyter Notebook, VS Code, Spyder, etc.) o en otra plataforma, debes tener en cuenta lo siguiente:

1. **Descargar los datos base:** Es estrictamente necesario que descargues la carpeta llamada **`Datos_crudos`**. En ella se encuentran todos los archivos Excel y CSV con los datos relevantes y parámetros operativos del caso Bebidas del Maipo S.A.
2. **Estructura de directorios:** Asegúrate de mantener la carpeta `Datos_crudos` en la misma ubicación relativa que el notebook, o en su defecto, actualiza la variable de la ruta de lectura (`ruta_base`) en los primeros bloques del código para que los datos carguen correctamente.
3. **Requisitos e Instalación:** Necesitarás un entorno con Python instalado. Te recomendamos instalar las librerías requeridas ejecutando el siguiente comando en tu terminal o consola:
   ```bash
   pip install pandas numpy matplotlib pulp statsforecast
