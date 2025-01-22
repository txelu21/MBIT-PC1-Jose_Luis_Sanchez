# MBIT-PC1-Jose_Luis_Sanchez

## Estructura de Archivos

```
MBIT-PC1-Jose_Luis_Sanchez/
├── data/                     # Directorio para datasets
│   ├── raw/                 # Datos originales
│   └── processed/           # Datos procesados
├── notebooks/               # Jupyter notebooks
│   └── wine_analysis.ipynb  # Notebook principal
├── src/                     # Código fuente
│   └── utils/              # Funciones auxiliares
├── requirements.txt         # Dependencias
└── README.md               # Documentación
```

## Dependencias Iniciales

El archivo `requirements.txt` contiene las siguientes dependencias:

- pandas
- numpy
- sqlite3
- jsonlines
- matplotlib
- seaborn
- jupyter
- requests

## Plan de Implementación por Fases

### Fase 1: Configuración Inicial

1. Crear la estructura de directorios
2. Inicializar el entorno virtual
3. Instalar dependencias
4. Configurar Git para commits

### Fase 2: Adquisición de Datos

1. Crear función para descargar datasets
2. Implementar verificación de integridad
3. Guardar datasets en data/raw/

### Fase 3: Procesamiento de Datos

1. Cargar datasets con pandas
2. Combinar datasets
3. Análisis exploratorio inicial
4. Detección y manejo de atípicos

### Fase 4: Base de Datos

1. Crear conexión SQLite
2. Diseñar esquema de tabla
3. Implementar consultas requeridas

### Fase 5: Exportación NoSQL

1. Transformación a formato JSON
2. Manejo de tipos especiales
3. Exportación a JSONLines

### Fase 6: Análisis de Calidad

1. Análisis estadístico
2. Visualizaciones
3. Documentación de hallazgos

## Consideraciones Técnicas

- Usar Git para control de versiones
- Documentar cada paso en el notebook
- Implementar manejo de errores
- Seguir PEP 8 para estilo de código
