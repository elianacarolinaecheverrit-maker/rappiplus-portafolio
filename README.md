RappiPlus | Rentabilidad, embudo de compra y retención
Proyecto final del Sprint 12 · Bootcamp de Análisis de Datos de TripleTen
Herramientas: Python, SQL, Jupyter Notebook y Power BI
Período de pedidos analizados: enero a junio de 2025

Problema
El equipo de RappiPlus necesitaba entender cuánto aportaban los pedidos después de descontar el costo de los productos y el gasto de marketing, en qué etapa del proceso de compra se reducía más el número de usuarios y cuántos volvían después de registrarse.

Qué hice
Python: revisé y depuré los datos de pedidos, catálogo y marketing. Calculé indicadores de ingresos, costos, margen y ticket promedio, y comparé el desempeño por país y producto.
SQL: construyó un embudo con usuarios únicos por evento y calculó la retención semanal de cohortes agrupadas por meses de registro.
Power BI: diseñó un panel ejecutivo para seguir los indicadores de ventas y una página de detalle para explorar el desempeño por producto.
Resultado y aprendizaje
Calidad de datos. Conservé 24.906 de 25.100 pedidos para el análisis, equivalentes al 99,23 % de los registros iniciales.
Rentabilidad. El resultado después de descontar el costo de producto y el gasto de marketing fue de 2.909.306,40 , equivalente al 30,27% de los ingresos . Para calcular la utilidad neta habría que incluir los demás costos operativos.
Proceso de compra. La mayor diferencia de alcance fue entre el inicio del checkout y el registro de la información de pago, con 958 usuarios menos . Como los usuarios se contaron por separado en cada evento, este hallazgo indica dónde investigar la fricción. Medir el abandono individual requiere seguir la secuencia de eventos de cada usuario.
Archivos del proyecto
Notebook con el análisis en Python y SQL
Informe para abrir en Power BI Desktop
Vista del tablero ejecutivo de RappiPlus
