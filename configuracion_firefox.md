#Configuracion Firefox

La ultima version de Firefox no soporta Selenium IDE, el cual es indispensable para esta porcion del curso, y para hacer prototipos rapidos en Selenium.  Se puede utilizar la version 53 del navegador, pero este se actualizara automaticamente una vez que se reinicie.  Para evitar esto, siga las instrucciones:

* Baje el [navegador](https://ftp.mozilla.org/pub/firefox/releases/53.0.3/)

* Desconecte la wifi

* Desinstale la version de Firefox existente, en caso de ser necesario.

* Instale la version 53 del navegador.

* Abra Firefox y navegue a la configuracion del browser en una nueva pestana:

```about:config```

* En el campo de busqueda, ingrese:

```app.update.auto```

y cambie el valor a false

* En el campo de busqueda, ingrese:

```app.update.enable```

y cambie el valor a false

* En el campo de busqueda, ingrese:

```app.update.silent```

y cambie el valor a false

* Reconecte la wifi y continue con la configuracion de Selenium IDE.