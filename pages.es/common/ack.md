# ack

> Una herramienta de búsqueda como grep, optimizada para programadores.
> Más información: <https://beyondgrep.com/documentation/>.

- Encuentra todos los archivos que contienen "foo":

`ack {{foo}}`

- Encuentra archivos de un tipo específico, como `ruby`:

`ack --ruby {{foo}}`

- Cuenta el total de número de coincidencias para el término `foo`:

`ack -ch {{foo}}`

- Muestra los nombres de archivo que contienen `foo` y el número de coincidencias en cada uno:

`ack -cl {{foo}}`

- Busca una determinada cadena de caracteres en un archivo:

`ack "{{bar}}" {{path/to/file}}`

- Busca coincidencias de la expresión regular en un archivo determinado:

`ack "{{[bB]ar \d+}}" {{path/to/file}}`

- Lista todos los tipos admitidos:

`ack --help-types`
