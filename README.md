# Simulación de valuación-de-riesgos-proveedores

Este proyecto simula la identificación, evaluación y priorización de riesgos no financieros asociados a proveedores externos, incluyendo riesgos operacionales, tecnológicos, legales y de ciberseguridad. Permite calcular indicadores clave (KRI) y generar reportes en Excel.

## Estructura de trabajo
```
├── data/
│   └── proveedores.csv                  # Dataset ficticio de proveedores y riesgos
├── notebooks/
│   └── evaluacion_riesgos.ipynb         # Notebook de análisis en Python
├── reports/
│   └── reporte_riesgos.xlsx             # Reporte generado automáticamente
├── README.md                            # Descripción del proyecto
└── requirements.txt                     # Librerías necesarias
```

## Requisitos
- Python 3.8 o superior
- Jupyter Notebook
- pip

## Cómo usar

### Clonar el repositorio
```bash
git clone https://github.com/darrentinoc/valuacion-de-riesgos-proveedores.git
cd valuacion-de-riesgos-proveedores
```

### Instalar dependencias
```bash
pip install -r requirements.txt
```

### Ejecutar el notebook
```bash
jupyter notebook notebooks/evaluacion_riesgos.ipynb
```

## Funcionalidades
- Calcular score total de riesgo por proveedor
- Identificar proveedores críticos
- Generar indicadores clave de riesgos (KRI)
- Exportar resumen completo a Excel

## Tecnologías
- Python (pandas, matplotlib, seaborn)
- Excel (vía openpyxl)
- Dataset ficticio para simulación

---

**Autor**: Darren Tinoco  
**GitHub**: [https://github.com/darrentinoc]
**Fecha**: Julio 2025

## Licencia
Solo para fines educativos y de simulación. No se debe utilizar para decisiones reales de negocio. Este proyecto no es un asesoramiento financiero o legal.