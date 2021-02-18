# reactjs-test

Objetivos:

1- Crear una aplicación react (se puede utilizar [CRA](https://create-react-app.dev/))

2- Consumir API de resultado de hoteles: https://basset.free.beeceptor.com/reactjs-test/accommodations

3- Renderizar los clusters de hoteles en una listado ajustandose correctamente para mobile (diseño https://www.figma.com/file/6pc1svdak2qrGKrXCBAy10/Cluster-hoteles?node-id=1%3A357)

4- La app tiene que tener un tema de colores configurado que permita elegir el color de fondo del cluster (default: #FFFFFF) y el color de fondo del botón "Ver hotel" (default: #126AFF). Estos dos colores tienen que ser modificables en dos inputs dentro de la app.

Requerimientos:

* La única libreria que se puede agregar además de las que instala [CRA](https://create-react-app.dev/) es [Material-UI](https://material-ui.com/)
* Utilizar la nueva API de Hooks de react
* Utilizar la nueva api de Context de react

Aclaraciones:

* Ignorar el resto de los campos que no esten dentro de `clusters` en el json de respuesta de la API
* Limite máximo de pantalla mobile: `425px`
