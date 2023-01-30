Tenemos la siguiente lista de productos (https://dummyjson.com/products?limit=100). Construir y hacer test sobre ese array de productos:

- Crear un proyecto e2e con las configuraciones vistas en clase (git, husky, editorconfig, prettier, lint, jest, typescript, sonar y netlify)
- Copiar este JSON en un archivo data.ts en src y exportarlo en una constante.

Crear las siguientes funciones y testarlas, cada una en una carpeta y dentro su archivo:

- Función que reciba la lista de productos y devuelva los productos sin stock
- Función que reciba un producto y calcule el precio con descuento
- Función que devuelva la lista ordenada por rating
- Función que devuelva dado una marca y una categoría, devuelva la lista de productos que contengan esa marca y categoria
- Función que dada una lista de productos devuelva el total con descuento
- Función que dado un preció máximo y uno mínimo, devuelva la lista de productos cuyo precio con descuento se encuentre en ese rango

Mostrar el resultado de cada función en con datos de ejemplo en el HTML
