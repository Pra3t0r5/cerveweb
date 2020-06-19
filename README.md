![splash](https://github.com/Pra3t0r5/cerveweb/blob/master/splash.png?raw=true)

# CerveWeb #

Website oriented to the commercialization of craft beers through orders and delivery initiated by registered customers.
Sitio web orientado a la comercializacion de cervezas artesanales por medio de pedidos y delivery iniciados por clientes registrados.

## Love Life, Love Birra ##

* **Author:** Fernando Albertengo (Pra3t0r5)
  * [Portfolio](http://falbertengo.com.ar)
  * [Webmaster](https://webmaster.cerveweb@gmail.com)
  * [Email](https://fernando.albertengo@gmail.com)
* **Stack:** Flask - SqlAlchemy/Marshmallow - MySQL
* **Version:** 0.9.0 (June 2020)
* **License:** [MIT](LICENSE)

### Tech ###

The site is built using Python 3 with various Flask compatible modules like:

* flask_sqlalchemy
* flask_login
* flask_admin
* flask_marshmallow

It also has a security layer managed by:

* werkzeug.security

Marshmallow and SqlAlchemy are fully merged to give the advantage to work with serializable and json typed requests at will. This also gives the hability to switch or share the persistence layer to an external API, wich ensures not only a good degree of scalability, but the possibility to also connect to a future mobile app.

In version 1.0 the project will integrate a full admin dashboard with full control and including stock management module. Along with various fixes.

### Setup ###

Execute this script, please notice that you need to input sudo permissions to install all dependencies

~~~bash
git clone https://github.com/Pra3t0r5/cerveweb.git && cd cerveweb && chmod +x install.sh debug.sh && sudo ./install.sh
~~~

### Debugging ###

Then to launch just execute:

~~~bash
./debug.sh
~~~
