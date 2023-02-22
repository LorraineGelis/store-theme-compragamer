# Store Theme Compra Gamer 
## Información General:
Repositorio que contiene el clone de la tienda Compra Gamer basado en VTEX IO.

![Preview](../assets/imgDocs/preview.png)

## Configuraciones:
### Ejecute los siguientes pasos:

### 1 - Configuración básica:
En primera instancia debes tener instalado la interfaz de línea de comandos vtex, importante, tener un ambiente/espacio de trabajo desarollador en el que puedas trabajar.

Para terminar, [Aquí Acceda a la guía de configuración básica](https://vtex.io/docs/getting-started/build-stores-with-store-framework/1) de VTEX IO y sigue todos los pasos que la guía te indica.

### 2 - Clonar el repositorio:

Debes [Clonar](https://github.com/LorraineGelis/store-theme-compragamer) el repositorio en tu ambiente local, esto con el fin, de que puedas acceder a el e iniciar a trabajar. Una vez clonado, puedes abrirlo en tu editor de codigo preferido.

###  3 - Editar el Manifest.json:

Una vez tengas el repositorio clonado, ahora, es el momento de editar el archivo `manifest.json`. Cuando te encuentres en dicho archivo, deberas reemplazar `vendor` y `name`. en donde: `vendor` es el nombre de la cuenta del partner en la que está trabajando, para este caso es itgloberspartnercl y `name` puede ser cualquier nombre que desee para su tema/tienda. Por ejemplo:

```json
{
  "vendor": "itgloberspartnercl",
  "name": "store-compragamer",
}
```

###  4 - Instalación de Apps:

Para usar Store Framework y trabajar en el tema de la tienda seleccionada, es necesario e importante tener instalado lo siguiente: `vtex.store-sitemap` y `vtex.store`. Si no está seguro de sus instalaciones Ejecute `vtex list` y así verifique si esas aplicaciones están instaladas.

Si no se encuentran instaladas, ejecute el comando `vtex install vtex.store-sitemap vtex.store -f` para instalarlas.

### 5 - Desinstalar el store-theme por defecto:

Al ejecutar `vtex list`, puede validar si cualquier tema está instalado.

Es bastante normal tener instalado un `vtex.store-theme` predeterminado, esto sucede cuando inicia el proceso de desarrollo de la tienda. Entonces, si lo encuentra en la lista de aplicaciones, proceda a copiar su nombre y version, luego utilícelo junto con el comando `vtex uninstall`. Por ejemplo:

```json
vtex uninstall vtex.store-theme@0.0.1
```

### 6 - Vista previa de la tienda:

Para cargar todos los cambios que ha realizado en sus archivos locales ejecute el comando `vtex link`. Este comando lo que hace es linkear la aplicación.

Luego, proceda a ejecutar `vtex browser`. Este comando lo que realizará es abrir una ventana del navegador que tendrá su tienda vinculada. y Así podrá visualizar todos los cambios en tiempo real. 

## Builders:
```json
  "assets": "0.x"
  "styles": "2.x"
  "store": "0.x"
  "docs": "0.x"
 ```

## Components:
    "vtex.store": "2.x",
    "vtex.store-header": "2.x",
    "vtex.product-summary": "2.x",
    "vtex.store-footer": "2.x",
    "vtex.store-components": "3.x",
    "vtex.styleguide": "9.x",
    "vtex.slider": "0.x",
    "vtex.carousel": "2.x",
    "vtex.shelf": "1.x",
    "vtex.menu": "2.x",
    "vtex.minicart": "2.x",
    "vtex.product-details": "1.x",
    "vtex.product-kit": "1.x",
    "vtex.search-result": "3.x",
    "vtex.search": "2.x",
    "vtex.login": "2.x",
    "vtex.my-account": "1.x",
    "vtex.flex-layout": "0.x",
    "vtex.rich-text": "0.x",
    "vtex.store-drawer": "0.x",
    "vtex.locale-switcher": "0.x",
    "vtex.product-quantity": "1.x",
    "vtex.product-identifier": "0.x",
    "vtex.product-specification-badges": "0.x",
    "vtex.product-review-interfaces": "1.x",
    "vtex.telemarketing": "2.x",
    "vtex.order-placed": "2.x",
    "vtex.stack-layout": "0.x",
    "vtex.tab-layout": "0.x",
    "vtex.responsive-layout": "0.x",
    "vtex.slider-layout": "0.x",
    "vtex.iframe": "0.x",
    "vtex.breadcrumb": "1.x",
    "vtex.sticky-layout": "0.x",
    "vtex.add-to-cart-button": "0.x",
    "vtex.modal-layout": "0.x",
    "vtex.store-icons": "0.x",
    "vtex.checkout-summary": "0.x",
    "vtex.product-price": "1.x",
    "vtex.store-link": "0.x",
    "vtex.product-list": "0.x",
    "vtex.disclosure-layout": "1.x"

  ## Custom Apps:
```json
    "itgloberspartnercl.whatsapp-button": "0.x",
    "itgloberspartnercl.bullets-diagramation": "0.x",
    "itgloberspartnercl.add-to-cart-info": "0.x",
    "itgloberspartnercl.custom-department-search": "0.x",
    "itgloberspartnercl.pdf-reader": "0.x",
    "itgloberspartnercl.quick-order": "0.x",
    "itgloberspartnercl.special-diagramation": "0.x",
    "itgloberspartnercl.up-button": "0.x"
 ```

### Colaboradores:

- Lorraine Gelis Díaz
    



