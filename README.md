# 🧪 Herramientas de Química Computacional

Este repositorio contiene herramientas interactivas de Python para cálculos y visualizaciones de química, diseñadas para estudiantes y profesionales de química.

## 📋 Descripción

Una colección de notebooks de Jupyter que proporcionan funciones y herramientas para resolver problemas comunes de química, incluyendo cálculos de peso molecular, conversiones de unidades, pH, ley de gases ideales, y más.

## 🚀 Características

- **Cálculos de peso molecular** - Calcular pesos moleculares usando masas atómicas
- **Conversiones de unidades** - Convertir entre gramos, moles, y otras unidades
- **Cálculos de pH y pOH** - Determinar acidez y basicidad de soluciones
- **Ley de gases ideales** - Calcular presión, volumen, temperatura y cantidad de gas
- **Concentración y molaridad** - Calcular concentraciones de soluciones
- **Balanceo de ecuaciones químicas** - Herramientas para balancear reacciones
- **Visualización de datos** - Gráficos y visualizaciones para análisis químico

## 📁 Estructura del Proyecto

```
quimica/
├── README.md                    # Este archivo
├── chemistry_notebook.ipynb     # Notebook principal con herramientas de química
└── chemistry_class.ipynb       # Notebook para clases y ejercicios
```

## 🔧 Requisitos

Para ejecutar estos notebooks necesitas:

- Python 3.7+
- Jupyter Notebook o JupyterLab
- Las siguientes librerías de Python:
  ```
  numpy
  pandas
  matplotlib
  ```

## 💻 Instalación y Uso

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/IgnacioPalma/quimica.git
   cd quimica
   ```

2. **Instala las dependencias:**
   ```bash
   pip install numpy pandas matplotlib jupyter
   ```

3. **Ejecuta Jupyter:**
   ```bash
   jupyter notebook
   ```

4. **Abre los notebooks:**
   - `chemistry_notebook.ipynb` - Para herramientas y cálculos interactivos
   - `chemistry_class.ipynb` - Para ejercicios y clases

## 📚 Uso de los Notebooks

### Chemistry Notebook (`chemistry_notebook.ipynb`)

Este notebook incluye funciones para:

- **Cálculo de peso molecular**: Usar el diccionario de masas atómicas para calcular pesos moleculares
- **Conversiones de unidades**: Funciones para convertir entre diferentes unidades químicas
- **Cálculos de gases**: Aplicar la ley de gases ideales
- **Análisis de soluciones**: Calcular pH, pOH, concentraciones

### Ejemplo de Uso

```python
# Calcular peso molecular del agua (H2O)
h2o_weight = calculate_molecular_weight({'H': 2, 'O': 1})
print(f"Peso molecular del H₂O: {h2o_weight:.3f} g/mol")

# Convertir gramos a moles
moles = grams_to_moles(18.0, h2o_weight)
print(f"18.0 g de H₂O = {moles:.3f} moles")
```

## 🎯 Aplicaciones

Este proyecto es útil para:

- **Estudiantes de química** - Resolver problemas de tarea y estudiar conceptos
- **Profesores** - Crear material educativo interactivo
- **Profesionales** - Realizar cálculos rápidos y precisos
- **Investigadores** - Análisis de datos químicos y visualizaciones

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para contribuir:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 👨‍💻 Autor

**Ignacio Palma**
- GitHub: [@IgnacioPalma](https://github.com/IgnacioPalma)

## 🙏 Agradecimientos

- Inspirado en la necesidad de herramientas computacionales para educación química
- Gracias a la comunidad de Python científico por las excelentes librerías

---

*¿Tienes preguntas o sugerencias? ¡Abre un issue o contacta al autor!* 🚀 