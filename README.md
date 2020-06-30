# blog-medico-backend
 Backend basado en Strapi

Instalación:
npm install

Ejecución:
npm run develop

Administración:
En http://localhost:1337/admin 

Ir a plugins->content-types builder
Crear 'new content type' con nombre Article, campos title(text),content(rich text),image(media),published_at(datetime)
Crear 'new content type' con nombre Category, campos name(text),articles(relation)

Ir a collection types->categories
Crear dos categoria, por ejemplo Noticias,Eventos
Crear dos articulos, uno asignado a cada categoria

Ir a plugins->roles & permisions
Para el rol Public, tanto en Article como en Category, activar permissions find,findone
