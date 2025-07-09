# Sistema de Predicción de Aprobación de Tarjetas de Crédito usando Aprendizaje Automático

En elpresente proyecto se propone desarrollar un modelo de aprendizaje automático (Machine Learning) capaz de predecir si un solicitante será un “buen” o “mal” cliente. Este enfoque busca automatizar y optimizar el proceso de aprobación de tarjetas de crédito, permitiendo al banco reducir riesgos y mejorar la eficiencia del proceso de evaluación. La solución basada en Machine Learning permitirá no solo realizar predicciones, sino también adaptarse mejor a nuevas condiciones económicas o cambios en los patrones de comportamiento de los usuarios.

## Video de Explicación del Proyecto

Puedes ver un video explicativo del proyecto en el siguiente enlace: [Video de Explicación](https://youtu.be/5OUmXHCyvs8).

## ¿Cómo ejecutar el proyecto?

Para ejecutar el proyecto, puedes seguir los siguientes pasos para correr el código en tu entorno local. Asegúrate de tener instalado Python y Git en tu sistema.

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/ValentinaCadena/CreditApprovalML.git
   ```
2. **(Opcional) Crear un entorno virtual**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # En Linux/Mac
   venv\Scripts\activate  # En Windows
   ```

3. **Instalar las dependencias**:

   ```bash
    pip install -r requirements.txt
   ```

4. **Ejecutar los bloques de código**:
   - Abre el archivo `main.ipynb` en Jupyter Notebook o en tu entorno de desarrollo preferido.
   - Ejecuta cada celda para cargar los datos, entrenar el modelo y realizar las predicciones.

Otra opción es abrir el notebook directamente en Google Colab. Para ello, sigue estos pasos:

1. Abre Google Colab en tu navegador.
2. Haz clic en "Archivo" > "Subir cuaderno".
3. Selecciona el archivo `main.ipynb` que descargaste del repositorio.
4. Una vez cargado, deberás instalar las dependencias que se encuentran en el archivo `requirements.txt`. Puedes hacerlo subiendo el archivo `requirements.txt` al entorno de Colab o copiar su contenido y ejecutarlo en una celda de código:

   ```python
    !pip install -r requirements.txt
   ```

O puedes instalar las dependencias directamente en una celda de código:

```python
 !pip install pandas scikit-learn ... # Añade aquí las demás dependencias que se mencionan en el archivo `requirements.txt`
```

5. Ahora puedes ejecutar las celdas del notebook para cargar los datos, entrenar el modelo y realizar las predicciones.
