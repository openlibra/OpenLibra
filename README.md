OpenLibra
=========

Bienvenido a la guía de instalación de OpenLibra. Si desea instalar la versión actual de OpenLibra en su entorno de desarrollo deberá seguir los pasos que se detallan a continuación.

1) Clonar el repositorio git
----------------------------

    git clone https://github.com/openlibra/OpenLibra.git

2) Renombrar el archivo parameters.ini
--------------------------------------

	cp app/config/parameters.ini.dist app/config/parameters.ini

3) Instalar las librerías dependientes
--------------------------------------

	php bin/vendors install

