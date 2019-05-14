# Paper Dashboard 1 - VueJS1
Documentation of PapeDashboard Version


#### SideBar.vue
/src/components/UIComponents/SidebarPlugin/SideBar.vue

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
/src/assets/sass/paper/_sidebar-and-main-panel.scss

y aquí podemos encontrar entre otras cosas la clase que usa la imágen del logo y el texto:   
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




