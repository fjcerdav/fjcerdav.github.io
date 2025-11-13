# cancionerocatolico
Este es un derivado del plugin JQuery Transposer con algunas adaptaciones:

- Está en notación latina (DO, RE, MI..) por lo cual la función que identifica si la línea es de acordes o no detecta en positivo (cualquier línea donde detecte un acorde, será línea de acorde).

- Permite utilizar elementos de fraseo, para por ejemplo usar negritas en el estribillo de la canción.

  DETALLES IMPORTANTES
  - La letra de la canción va envuelta dentro de un texto preformateado <pre> </pre> con el id "letra" y un valor data-key que es la tonalidad de la canción.
  - Usar tipografía monospace para garantizar que no se desplacen los acordes durante la transcripción.
  - Que los nombres de acordes estén en mayúscula (DO, RE, MI..), los restantes elementos pueden ir en minúscula sin problema (por ej. SIb7, SIm7b5). Y evitar escribir dos mayúsculas seguidas en la letra de la canción.
  - Respecto al data-key, al agregarle una m al final (por ejemplo data-key="REm", el script usará armaduras de clave para tonalidades menores. En caso contrario, data-key="RE" usará tonalidades mayores.

Ejemplo:   https://fjcerdav.github.io/index.html 
