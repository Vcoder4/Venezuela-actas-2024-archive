# Repositorio creado con el propósito de proteger la integridad de todas las actas recolectadas hasta ahora e intentar centralizar la información un poco.

## [Página origen de Comando ConVzla: Resultados con Venezuela](https://resultadosconvzla.com/)
- Repositorios en GitHub
  - [Escaner de actas](https://github.com/Strvm/vnzla-libre)
    - Función: Escaneo del qr y procesamiento de esa información
    - Lenguajes: Python
  - [Crawler y escaner](https://github.com/xaiki/resultadosvzla-tools)
    - Función: Descarga de las actas y escaneo del qr
    - Lenguajes: Python y Shell
  - [Crawler](github.com/Eitol/verificador_elecciones2024_ve)
    - Función: Descarga de las actas
    - Lenguajes: Go
- Descargas alternas
  - [22817 actas (Mediafire) en 6 archivos](https://www.mediafire.com/folder/p1i5nx46yktay) incompleto de [fuente independiente](https://github.com/Eitol/verificador_elecciones2024_ve).
  - [24048 actas (Google Drive)](https://drive.google.com/drive/folders/1I_Ae22mpHUg4xJGz1WTv_F5J8g2zTwqm) incompleto de [fuente independiente](https://github.com/xaiki/resultadosvzla-tools).
  - [27367 actas (GitHub)](https://github.com/Strvm/vnzla-libre/tree/main/images) completo de fuente independiente.
- Actas totales, ¿Cuántas son?
  - `24532` de [RESULTADOS_2024_CSV_V1.csv](https://static.resultadosconvzla.com/RESULTADOS_2024_CSV_V1.csv).
  - `2642` de multiples fuentes (no registrados en [RESULTADOS_2024_CSV_V1.csv](https://static.resultadosconvzla.com/RESULTADOS_2024_CSV_V1.csv)).
  - Dan un número total de `27174` actas, sin duda hay muchos duplicados ya que en https://resultadosconvzla.com/ está indicado que son `24532`, o talvez no son duplicados, sino `actas no registradas`.
- Comprobación de actas
  - En este repositorio están datos que pueden ayudar a verificar la `integridad criptográfica` de todas las actas escaneadas (que tengo), en caso de que alguien esté interesado, o simplemente por curiosidad (como yo XD).
    - `nombre`, `hash(sha256)` y `tamaño` para las [24532 actas del csv](https://raw.githubusercontent.com/Vcoder4/Venezuela-actas-2024-archive/main/24532%20actas%20sha256.json), y [2642 actas no listadas en el csv](https://raw.githubusercontent.com/Vcoder4/Venezuela-actas-2024-archive/main/2642%20actas%20sha256.json)
