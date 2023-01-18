1. Borramos la carpeta home
2. creamos la pagina principal
    - --spec=false No crea los archivos de prueba.
    - --dry-run Muestra lo que se va a crear.
```
    ionic g page pages/inicio --sky-tests
``` 
3. Creamos la pagina alert
```
    ionic g page pages/alert --spec=false
```
4. Creamos la pagina action-sheet
```
    ionic g page pages/action-sheet --spec=false
```
5. Creamos un modulo para los componentes
```
    ionic g module components
```
6. Creamos un componente personalizado
```
    ionic g component components/header --spec=false
```

# Otros

- Documentación UI Components de ionic
    - https://ionicframework.com/docs/components