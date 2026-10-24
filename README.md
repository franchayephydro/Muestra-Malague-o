# Mapas de Malagueño

Mapa web interactivo (Leaflet) con tres mapas temáticos del municipio de Malagueño, Córdoba:

1. **Parcelas**: estado de edificación (baldío / edificado / edificado PH). Número de parcela desde 1:2.500; más alejado, sólo el número de manzana.
2. **Usos del suelo IPLAM**: Plan Metropolitano de Córdoba.
3. **Cobertura y uso actual del suelo 2024–2025**: ráster IDECOR (10 m, 21 clases) recortado al ejido (radio urbano) de Malagueño, reproyectado a Web Mercator como imagen indexada (`data/cobertura_2024_2025.png` + `data/cobertura_2024_2025.json` con límites y superficies por clase dentro del radio urbano).

Todos incluyen el radio urbano de Malagueño.

Datos convertidos desde GeoPackage (POSGAR 98 / Argentina 4 y 3) a GeoJSON WGS 84 (EPSG:4326), carpeta `data/`.
