# Vue Paper Dashboard v1
Este repositorio sirve como documentacion sobre los principales componentes del Dashboard de VueJS.  

Aqui se describiran los componentes principales, y que funcion tiene cada uno.    


### SideBar.vue
```
/src/components/UIComponents/SidebarPlugin/SideBar.vue    
```   
Aquí se cambia el título principal del Dashboard, la imágen del Logo, y varias cosas mas del menú lateral Izquierdo.   
 Todo esto en la seccion de las __PROPS__

```js
export default {
    title: {
            type: String,
            default: 'Sistema de Gestión Ingeo'
          },
    props: {
      logo: {
              type: String,
              default: 'static/img/logo-ingeo.png'
            },
```

El estilo de este componente es ___sidebar-and-main-panel.scss__   
```
/src/assets/sass/paper/_sidebar-and-main-panel.scss   
```
Y aquí podemos encontrar entre otras cosas la clase que usa la imágen del logo y el texto:    
```css
    .logo-img{
        width: 34px;
        display: inline-block;
        height: 34px;
        margin-left: 0px;
        margin-right: 10px;
        background: white;
        border-radius: 40px;
        text-align: center;

      img{
          // max-width: 18px;
          max-width: 30px;
          position: relative;
      }
```

### sidebarLinks.js   
```
/Users/alejandrodecastro/IngeneaProjects/sgi-web/src/sidebarLinks.js
```
Este archivo maneja los componentes que se mostrarán en todo el Dashboard, es fundamental para mostrar u ocultar nuestros componentes.   

```js
export default [

  {
    name: 'Vehículos',
    icon: 'ti-car',
    path: '/admin/ingresoPatente'
  }
]
```

En el caso de querer agregar otro item, sensillamente se agrégará otro objeto al array, de esta manera:   

```js
export default [

  {
    name: 'Vehículos',
    icon: 'ti-car',
    path: '/admin/ingresoPatente'
  },
  {
    name: 'Otro Menu',
    icon: 'ti-user',
    path: '/admin/otracomponente'
  }
]
```

### TopNavbar.vue
```
/src/components/Dashboard/Layout/TopNavbar.vue
```
Este componente tiene toda la barra superior, podriamos pensarlo como un Header.   


### ContentFooter.vue
```
/src/components/Dashboard/Layout/ContentFooter.vue
```
Este componente tiene todo lo relacionado con el Footer del Dashboard, alli se pueden cambiar los copyright y demas   


### UserMenu.vue
```
/src/components/UIComponents/SidebarPlugin/UserMenu.vue
```
Este componente tiene los datos del Menu del usuario logueado.   

### index.html
```
/Project-Name/index.html
```
Aca se configura el titulo del proyecto, y el icono que tendra la App.   

