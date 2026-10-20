# Visor Ambiental · Valle de Aburrá

Visor web 3D del Área Metropolitana de Medellín (un único archivo HTML, MapLibre GL, sin claves de API).

Abrir `visor_ambiental_amva.html` en el navegador (requiere internet).

## Capas
- **Relieve 3D**: AWS Terrain Tiles (terrarium), hillshade y curvas de nivel generadas en el navegador.
- **Mapas base**: Esri World Imagery, Sentinel-2 cloudless 2021 (EOX), OpenStreetMap.
- **Índices NASA GIBS**: NDVI, EVI, temperatura superficial, AOD, NO₂, VIIRS.
- **Cobertura vegetal**: Sentinel-2 y Landsat (Esri ImageServer): falso color infrarrojo, agricultura, SWIR, NDVI, NDMI, NBR, NDBI; Landsat con selector de año (1985–2025).
- **Deforestación**: Hansen Global Forest Change (cobertura 2000, pérdida 2001–2023, ganancia).
- **Hidrología**: ríos, quebradas y cuerpos de agua de OpenStreetMap (Overpass).
- **Denuncias ambientales**: 10 categorías con filtros. Las precargadas son **datos ficticios de ejemplo**; las nuevas se guardan en el navegador.
