# Segmentación y Modelado Predictivo de Clientes Jóvenes

> Análisis de comportamiento financiero, satisfacción y preferencias de 800 clientes jóvenes (18–30 años) para identificar oportunidades de mejora en la experiencia de la app.

**Aviso:** proyecto académico/de práctica, no afiliado al BCP.

## 🎯 Problema de negocio
¿Qué falla en la experiencia de la app para clientes jóvenes, y dónde hay oportunidades medibles de mejora?

## 📊 Datos
- Tamaño: 800 clientes, variables de comportamiento financiero, uso digital, satisfacción y preferencias.
- Origen: Reclutador de BCP.
- Limpieza: valores faltantes, outliers, codificación de variables categóricas.

## 🧪 Metodología
1. **Limpieza y EDA** con pandas y NumPy.
2. **Segmentación:** clustering en 4 perfiles según comportamiento financiero y digital.
3. **Validación estadística:** comprobación de que las diferencias entre perfiles son significativas (no producto del azar).
4. **Modelado predictivo:**
   - Modelo A: probabilidad de que un cliente ahorre.
   - Modelo B: probabilidad de que deje de usar una función de la app.
5. **Dashboard interactivo** en Power BI con medidas DAX para exploración por parte del equipo de producto.

## 📈 Resultados principales
- El **58%** de los clientes usa la app a diario sin lograr ahorrar.
- El **29%** abandonó alguna función; el **53%** de esos casos lo atribuye a que la percibe compleja o poco útil.
- La satisfacción promedio con la app es de **3.4 / 5**.
- La mayoría confía más en su familia o comunidad que en el banco para decisiones financieras.

Para el dashboard: abrir `dashboard/dashboard_bcp.pbix` con Power BI Desktop.

## ⚠️ Limitaciones
- Muestra de 800 clientes; los resultados no son generalizables a toda la base del banco.
- Encuesta de satisfacción con posible sesgo de autoselección.
- Los modelos son de demostración y no sustituyen una validación en producción.

## 👤 Autor
Juan Llauce · Estudiante de Estadística, UNMSM ·
