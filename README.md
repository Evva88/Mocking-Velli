# Mocking

Proyecto de backend entrega con Mock

El proyecto esta compuesto por las siguientes partes:
Carpeta src, la cual a su vez reune dentro suyo a:

1. Config, que guarda dentro suyo a config.js (donde se aloja dotenv).
2. Controllers, figuran aqui todos los controladores que trabajaran con los servicios (auth, cart, products, user, messages, sms, tickets).
3. Dao, gracias a esta gran carpeta podemos ver organizado todo lo siguiente:
A. Carpeta Dtos donde encontraremos a los DTOS de factory, user y user.response.
B. Carpeta fs donde estan los archivos file sistem.
B. Carpeta models, hay aqui todos los modelos necesarios para poder trabajar tanto con los usuarios como los mensajes, los carritos, los tickets y los productos.
C. Junto a estas carpetas tambien encontraremos en dao a todos los managers para trabajar con los modelos nombrados anteriormente.
5. Memory donde tenemos al contectMemo.js.
6.  MidsIngreso, quien alberga a bcrypt.js(proteccion de informacion), github.js(acceso con esta plataforma), passAuth.js(autorizacion para ingreso) y passport.js(trabaja con passport).
7. Carpeta Mocking la cual engloba a todas las partes del mock (utils, controller y router).
8. Carpeta Mongo que contiene las partes para enlazar con la BD.
9. Carpeta Public, la cual es otra gran carpeta que contiene a:
A. Carpeta css la cual contiene los estilos del proyecto.
B. Carpeta images solo contiene el logo del cliente.
C. Carpeta js, sostiene dentro de si a login.js y a restore js.
D. Por ultimo y no en importacia tambien aqui encontraremos a los archivos: cart.js, chat.js, realTimeProducts.js, register.js  y user.js.
10. Carpeta repository donde encontramos a contacts.repository e index.
11. Routes, por aqui pasaran todas las rutas para unir a la app con las vistas a los diferentes sectores de la pagina.
12. Carpeta models, hay aqui todos los modelos necesarios para poder trabajar tanto con los usuarios como los mensajes, los carritos y los productos.
13. Services, quien aloja a todos los servicios que trabajaran con los controladores y tambien a las carpetas y dependencias de errores.

Carpeta view donde estan las vistas de la pagina, la cual contiene a layouts(donde encontraremos a main.handlebars) y tambien a las vistas de cart, products, product detail, login, register, restore, profile, chat y real time products

Env., quien trabaja reservando las variables para dotenv.

App.js, donde confluyen todos para darle vida a la pagina, trabaja con express, handlebarss, socket.io, mongoose, morgan, cookie-parser y los enrutadores.

_Utils js, donde se encuentra al _dirname.
