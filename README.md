# MLY1101 — Taller 1: Consumo Automatizado de APIs

**Nombre:** Christian Tapia

**Sección:** MLY1101_001V

**Pregunta u objetivo:** ¿Qué información puede recopilarse sobre videojuegos free-to-play, sus plataformas y el contenido jugable que ofrecen?

---

**API 1:** MMOBomb Games API — https://www.mmobomb.com/api — endpoint `https://www.mmobomb.com/api1/games`

**API 2:** FreeToGame — https://www.freetogame.com/api-doc — endpoint `https://www.freetogame.com/api/games`

**API 3:** YGOPRODeck (Yu-Gi-Oh! API) — https://ygoprodeck.com/api-guide/ — endpoint `https://db.ygoprodeck.com/api/v7/cardinfo.php?format=Duel%20Links`

---

**Registros API 1:** 414 registros.

**Registros API 2:** 415 registros.

**Registros API 3:** 8230 Registros.

---

## Archivos generados

| Archivo | Fuente |
| --- | --- |
| `dataset_api_1.csv` | MMOBomb |
| `dataset_api_2.csv` | FreeToGame |
| `dataset_api_3.csv` | YGOPRODeck (formato Duel Links) |

Los tres archivos son generados automáticamente por el código del notebook. No se realizó merge, join, concat ni cruce entre los datasets.

## Ejecución

Abrir `MLY1101_001V_T01_TapiaChristian.ipynb` en Google Colab y usar **Entorno de ejecución → Ejecutar todas**. Ninguna de las tres APIs requiere API key ni modificaciones manuales al notebook.
