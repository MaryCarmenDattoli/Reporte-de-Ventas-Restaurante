# 📊 Reporte de Ventas - Análisis de Restaurante

Análisis completo de ventas de un restaurante estilo europeo utilizando datos del sistema POS Pixel. Este proyecto incluye visualizaciones interactivas creadas con Plotly y una presentación dinámica publicada en QuartoPub.

## 🎯 Objetivo

Generar un reporte automatizable para el seguimiento de ventas que responda preguntas clave sobre:
- **Ventas**: Nivel de ventas y comparación con años previos
- **Demanda**: Comportamiento del ticket promedio y demanda por día de la semana
- **Clientes**: Grados de repetición y frecuencia de visitas
- **Precios**: Distribución de precios de comida y bebidas

## 📋 Contenido del Proyecto

- `reporte_ventas.qmd` - Archivo principal de Quarto con la presentación completa
- `registro_pixel.txt` - Dataset con transacciones de ventas (2018-2024)
- `S12_Automatizacion_Reportes_Sesiones_SV.ipynb` - Notebook original con el análisis
- `_quarto.yml` - Configuración de Quarto
- `_publish.yml` - Configuración de publicación

## 🚀 Visualización en Línea

La presentación interactiva está publicada y disponible en:

🔗 **https://marycde.quarto.pub/reporte-de-ventas-89d5**

## 🛠️ Tecnologías Utilizadas

- **Python 3.14**
- **Pandas** - Análisis de datos
- **NumPy** - Operaciones numéricas
- **Plotly** - Visualizaciones interactivas
- **Quarto** - Generación de presentaciones y publicación

## 📦 Instalación

1. Clona este repositorio:
```bash
git clone https://github.com/MaryCarmenDattoli/Reporte-de-Ventas-Restaurante.git
cd Reporte-de-Ventas-Restaurante
```

2. Instala las dependencias de Python:
```bash
pip install pandas numpy plotly pyyaml nbformat ipykernel jupyter
```

3. Asegúrate de tener Quarto instalado:
   - Descarga desde: https://quarto.org/docs/download/

## 📊 Estructura del Análisis

### 1. Análisis de Ventas
- Evolución de ventas anuales
- Comparación año a año

### 2. Análisis de Demanda
- Comportamiento del ticket promedio
- Análisis de comandas por día de la semana
- Preferencias de consumo por tipo

### 3. Análisis de Clientes
- Participación por tipo (Repetidores vs. De una ocasión)
- Grados de repetición (Fiel, Habitual, Esporádico)

### 4. Análisis de Precios
- Distribución de precios de comida
- Distribución de precios de bebidas

## 🔄 Cómo Publicar

Para publicar actualizaciones en QuartoPub:

```bash
quarto publish reporte_ventas.qmd
```

Luego selecciona:
1. **Provider**: Quarto Pub
2. Ingresa tu usuario de QuartoPub
3. Especifica el nombre del documento

## 📝 Datos

El dataset `registro_pixel.txt` contiene transacciones de ventas a nivel de comanda, cliente y artículo con las siguientes columnas:
- `comanda_id`: Identificador único de la comanda
- `cliente_id`: Identificador único del cliente
- `tipo_articulo`: Categorización del artículo consumido
- `periodo`: Año de la comanda
- `mes`: Mes de la comanda
- `dia_semana`: Día de la semana (Lun = 1)
- `valor_venta`: Valor de la venta en USD
- `valor_cantidad`: Cantidad consumida del tipo de artículo

## 👤 Autor

**Ma. del Carmen Dattoli Erosa**

## 📄 Licencia

Este proyecto fue creado con fines educativos.

## 🔗 Enlaces Útiles

- [Quarto Documentation](https://quarto.org/)
- [Plotly Python Documentation](https://plotly.com/python/)
- [QuartoPub](https://quartopub.com/)

