---
layout: page
title: Reutilización de la Colección
permalink: /reuse/
collection: damaboba
---

Esta web, haciendo uso de Wax, se insipira en los [FAIR data principles](https://journal.code4lib.org/articles/13427) y, como tal, se esfuerza por hacer que las colecciones sean localizables, accesibles, interoperables y reutilizables, respetando en todo caso los derecho vigentes sobre los elementos cotnenidos.

El portal contiene un documento titulado `interactive_metadata_table` dentro de la carpeta `_includes`, procedente de Wax, que ayuda a complementar la web con [DataTables](https://datatables.net/) interactivas y CSVs descargables de los metadatos de la colección.

{% include interactive_metadata_table.html collection=page.collection %}
