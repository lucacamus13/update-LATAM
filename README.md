# Update LATAM Market

Este proyecto en Python automatiza la recolección, procesamiento y visualización de datos financieros clave para América Latina. Genera un **resumen gráfico semanal** con:

- 🏦 Tasas de política monetaria (Chile, Brasil, México, Colombia, EE.UU.)
- 💱 Tipo de cambio (monedas de LATAM frente al dólar)
- 🛢️ Precios de commodities clave para la región

---

## Objetivo

Automatizar un **dashboard económico-financiero** actualizado semanalmente, ideal para analistas, estudiantes de economía, inversionistas y profesionales de mercados emergentes. Los datos se presentan en tablas limpias y visuales, y se pueden compartir fácilmente en LinkedIn como contenido profesional.

---

##  Tecnologías utilizadas

- `Python 3.10+`
- `pandas`, `requests`, `BeautifulSoup`, `yfinance`, `matplotlib`
- APIs oficiales:
  - Banco Central de Chile (BCCh)
  - Banco Central de Brasil (BCB)
  - Banxico
  - Banco de la República de Colombia (BanRep)
  - (En desarrollo: FRED – Fed de EE.UU.)

---

## Estructura del proyecto

### 1. Política Monetaria

Obtención automática de tasas actuales y variaciones a 30 días de:

![Tasa LATAM](img/política_monetaria.png)


Calcula variaciones en puntos básicos  
Genera tabla en consola + imagen PNG con íconos de tendencia (`📈 📉 ➡️`)

---

### 2. Tipo de Cambio LATAM

Consulta de monedas vs. USD:

- CLP, BRL, MXN, COP, ARS

Incluye cotización actual, variación diaria y mensual.


---

### 3. Commodities

Seguimiento de precios y cambios de commodities estratégicos:

- **Petróleo (Brent)**
- **Cobre**
- **Oro**
- **Litio (ETF)**
- **Soja**
- **Café**
- **Hierro**

---

## Ejemplo de salida

