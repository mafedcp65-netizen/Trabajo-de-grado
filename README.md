# Trabajo de grado

Este repositorio contiene los 3 modelos entrenados para realizar un clasificador de registros de defunción para el Registro Poblacional de Cáncer de Manizales.

## Modelos incluidos

- **SVM**
- **Transformers**
- **Reglas**

## Requisitos generales

Para ejecutar los modelos de este repositorio se requiere lo siguiente:

- **Google Colab** para los modelos de **SVM** y **Transformers**
- **GPU en Google Colab** para el modelo de **Transformers**
- **Entorno local** para el modelo de **Reglas**
- Tener la base de datos de entrada 
- Verificar y ajustar las rutas de lectura y escritura antes de ejecutar cada notebook

## Requisitos específicos por modelo y como ejecutarlos

### SVM

Este modelo debe ejecutarse en **Google Colab**.

**Ejecución:**  
Abrir el notebook del modelo SVM en Google Colab, cargar la base de datos de entrada y ejecutar todas las celdas en orden.

---

### Transformers

Este modelo debe ejecutarse en **Google Colab con GPU**.

**Importante:**  
Después de ejecutar la primera celda, **se debe reiniciar la sesión obligatoriamente**. Luego, se deben volver a ejecutar las celdas desde la segunda celda y en orden.

**Ejecución:**  
1. Abrir el notebook en Google Colab.  
2. Activar GPU en el entorno de ejecución.  
3. Ejecutar la primera celda.  
4. Reiniciar la sesión obligatoriamente.  
5. Volver a ejecutar las celdas desde la segunda celda en orden.

---

### Reglas

Este modelo debe ejecutarse en **local**.

**Configuración necesaria:**  
- Tener **Python** y **Jupyter Notebook** funcionando en el equipo.  
- Tener instalados y configurados correctamente **medSpaCy** y **QuickUMLS**.  
- Verificar que la ruta de **QuickUMLS** esté correctamente definida en el notebook.
- Ajustar las rutas de entrada y salida antes de la ejecución.  

**Ejecución:**  
Abrir el notebook del modelo de reglas en el entorno local y ejecutar las celdas en orden.
