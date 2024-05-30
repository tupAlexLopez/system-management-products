# SISTEMA GESTION DE PRODUCTOS - GREISYGU$

## Descripción
Este proyecto forma parte de las **PPS( Practica Profesionalizante Supervisada )** la cual es una materia de la Universidad Tecnologica Nacional en donde soy parte de ella como Alumno.
* El objetivo de este proyecto es el de realizar una aplicacion web que permita a los usuarios de la organizacion *GREISYGU$* gestionar sus productos y categorias.
    * GREISYGU$ es la organizacion en la que forme parte durante el tiempo de cursado para realizar las practicas supervisadas.
    * Las practicas fueron supervisadas por las siguientes personas: 
        * Ing. Vargas, Carolina ( Profesora de la materia PPS )
        * Tec. en Prog. Barrios, Soledad ( Tutor academico )
        * Sandoval, Gustavo ( Dueño de la organizacion GREISYGU$ )

## Índice de contenidos
1. [Instalación](#instalación)
2. [Características](#características)
3. [Manual de Usuario](#manual-de-usuario)
## Instalación
1. Descarga el proyecto
    * Click aqui: https://github.com/tupAlexLopez/system-management-products/archive/refs/heads/main.zip
2. Dirigase al directorio donde se encuentra la API REST.
    * ``` $ cd greisygu-.sysadmin.api-rest ```
    * Sigue las indicaciones del README.md de la aplicacion.
3. Entra en el directorio del cliente visual.
    * ``` $ cd greisygu.client.angular ```
    * Sigue las indicaciones del README.md de la aplicacion.
4. Perfecto!

## Características
* Interfaz amigable
* Gestion sencilla de productos y categorias
* Filtrado de busqueda de productos por descripcion, disponibilidad y categorias.

## Manual de Usuario
* [HOME](#home)
* [ADMINISTRACION](#administracion)
    * [Gestion de categorias](#gestion-de-categorias)
        * [Agregar nueva categoria](#★-agregar-nueva-categoria)
        * [Modificar nueva categoria](#★-modificar-categoria-existente)
        * [Eliminar categoria existente](#★-eliminar-categoria-existente)
        * [Agregar nueva categoria](#★-agregar-nueva-categoria)
    * [Gestion de Productos](#gestion-de-productos)
        * [Agregar nuevo producto](#★-agregar-nuevo-producto)
        * [Modificar producto existente](#★-modificar-producto-existente)
        * [Deshabilitar/Habilitar producto existente](#★-deshabilitar-y-habilitar-un-producto-existente)
        * [Eliminar producto existente](#★-eliminar-un-producto-existente)
    * [Filtrado y busqueda de Productos](#filtrado-y-busqueda-de-productos)
        * [Filtrar por Disponibilidad](#★-filtrar-por-disponibilidad)
        * [Filtrar por categoria y disponibilidad](#★-filtrar-por-categoria-y-disponibilidad)
        * [Filtrar por Descripcion](#★-filtrar-por-descripcion)
        * [Filtrar por Descripcion, Categoria y Disponibilidad](#★-filtrar-por-descripcion-categoria-y-disponibilidad)


### HOME
####  Contiene el logo de la empresa junto con una bienvenida y una opcion para ir hacia la vista de  productos.
![1  inicio de la aplicacion](https://github.com/tupAlexLopez/system-management-products/assets/166257002/dbe22108-5cdf-4e83-819c-6d751f9b84f3)

#### La aplicacion contiene un panel de navegacion para ir hacia la diferentes vistas que tiene la aplicacion, solamente tenemos la vista Home y Administracion.
![1  Uso del sidenav](https://github.com/tupAlexLopez/system-management-products/assets/166257002/f98f69a0-704b-42d3-bd08-cf57fe21abcd)

### ADMINISTRACION
#### Click al boton para acceder a la vista de la Administracion.
![2  1ra forma de ir hacia vista de productos](https://github.com/tupAlexLopez/system-management-products/assets/166257002/0604c7fc-b590-4743-baad-4313d92712bd)

#### Tambien puede acceder desde el panel de navegacion.
![2  2da forma de ir hacia vista de productos](https://github.com/tupAlexLopez/system-management-products/assets/166257002/7abf539e-10d2-456b-9225-1ffb13a860eb)

#### Vista de la Administracion
![3  Vista administracion de productos - sin productos](https://github.com/tupAlexLopez/system-management-products/assets/166257002/102c85ac-d052-4745-8628-600b31c224ff)

#### Gestion de Categorias

##### Click al boton
![4  click administrar categorias](https://github.com/tupAlexLopez/system-management-products/assets/166257002/5424ef76-61e4-4718-abd9-425b321963ad)

##### Vista previa de la administracion de categorias.
![5  Vista de administracion de categorias](https://github.com/tupAlexLopez/system-management-products/assets/166257002/a2cb7eba-1da5-44f8-b18c-d628812b0423)
---

#### ★ Agregar nueva categoria
##### Click al boton.
![6  Click al boton nuevo de administracion de categorias](https://github.com/tupAlexLopez/system-management-products/assets/166257002/1a6faaa1-7813-4b55-8fbd-928add2c5c97)

##### Debe escribir el nombre de la categoria nueva y luego click al boton.
![7  Click al boton de guardar categoria nueva](https://github.com/tupAlexLopez/system-management-products/assets/166257002/91314d30-3939-4763-85a9-e0bc8b731372)

##### Vista previa de la administracion de categorias luego de guardar la categoria nueva.
![8  Visualizacion de la categoria guardada](https://github.com/tupAlexLopez/system-management-products/assets/166257002/ca90f783-92f3-407b-8093-7e5af5ee5ea7)
---

#### ★ Modificar categoria existente
##### Click al boton.
![9  Modificacion de la categoria creada recientemente](https://github.com/tupAlexLopez/system-management-products/assets/166257002/3b711277-4549-4707-b686-96f843b856f2)

##### Modifique la categoria y luego click al boton.
![10  Click al boton de guardar categoria modificada](https://github.com/tupAlexLopez/system-management-products/assets/166257002/c533a583-59f0-4a27-b4e2-79c821e4cc21)

##### Vista previa de la administracion de categorias luego de modificar una categoria existente.
![11  Visualizacion de la categoria modificada](https://github.com/tupAlexLopez/system-management-products/assets/166257002/ba8b3927-1b7d-49f1-bbe3-987f076b48ac)

#### ★ Eliminar categoria existente
##### Click al boton.
![12  Click al boton de eliminar categoria](https://github.com/tupAlexLopez/system-management-products/assets/166257002/429c7c45-84b1-4204-8826-65d12f237067)

##### Si desea realmente eliminar la categoria, click al boton **Si, estoy de acuerdo**. De lo contrario click al boton **No**.
![13  Click al boton de confirmar categoria a eliminar](https://github.com/tupAlexLopez/system-management-products/assets/166257002/fe280ed7-a880-45c5-8f02-99a7e7c7eb79)
---

#### Si no desea realizar mas cambios con respecto a las categorias, para cerrar la ventana, click al boton.
![14  Click al boton de cerrar administracion de categorias](https://github.com/tupAlexLopez/system-management-products/assets/166257002/9e236fe6-0ff0-44ca-8eca-a81e9eba8cbf)
---
#### Gestion de Productos

#### ★ Agregar nuevo producto
##### Click al boton.
![15  Click al boton de agregar producto](https://github.com/tupAlexLopez/system-management-products/assets/166257002/9a18d6d3-a772-4f90-b199-4e9dca202c60)

#### Vista previa del formulario en ventana modal para guardar un producto.
![16  Visualizacion del formulario de productos](https://github.com/tupAlexLopez/system-management-products/assets/166257002/44093aff-d698-4d65-96ee-8853894fb3a1)

#### El formulario contiene validaciones para asegurar que los datos sean correctos.
![17  Visualizacion de validaciones en el formulario](https://github.com/tupAlexLopez/system-management-products/assets/166257002/b40f5401-d6e3-4900-aa15-ef6c76746636)

#### Indique los datos requeridos por el formulario y luego click al boton.
![18  Click al boton de guardar nuevo producto](https://github.com/tupAlexLopez/system-management-products/assets/166257002/bdb5f4ba-f9e8-4f81-aa8f-8787ab7b4d12)

#### Vista de la administracion. Ahora que ya existen productos en el sistema, podemos realizar todas las funcionalidades que realiza la aplicacion.
![19  Vista de administracion de productos - con productos](https://github.com/tupAlexLopez/system-management-products/assets/166257002/875d9801-e9d0-42a4-a8c9-51680684b7b7)
---

#### ★ Modificar producto existente
##### Click al boton
![20  Click al boton de modificar producto](https://github.com/tupAlexLopez/system-management-products/assets/166257002/fedde90c-e0ea-4ba1-9049-31e90e208086)

##### Puede modificar cualquier campo, en este caso se mostrara un ejemplo para subir una imagen a un producto existente.
![21  Click para subir una imagen ](https://github.com/tupAlexLopez/system-management-products/assets/166257002/2362c05f-4adc-420e-8d54-1124669a3fec)
##### Luego seleccionado la imagen se visualizara en el formulario.
![22  Previsualizacion de la imagen a subir](https://github.com/tupAlexLopez/system-management-products/assets/166257002/00872958-5c97-4650-b78d-d5dbc00a8cdd)

##### Click al boton para modificar el producto.
![23  Click al boton de guardar producto modificado](https://github.com/tupAlexLopez/system-management-products/assets/166257002/54ab2c48-43f5-445d-aff0-e13bcf152b81)

##### La vista se actualizara y se podra visualizar los cambios realizados.
![24  Demostracion de imagen cargada](https://github.com/tupAlexLopez/system-management-products/assets/166257002/cd1f0fbd-7129-4887-a199-02fcd8fd37c8)
---

#### ★ Deshabilitar y habilitar un producto existente.
##### Click al boton 
![25  Click al boton de deshabilitar o habilitar producto](https://github.com/tupAlexLopez/system-management-products/assets/166257002/8cf68879-6041-4be7-97db-4405c422a543)
##### Si realmente desea deshabilitar el producto, debe confirmar su eleccion dando click al boton **Si, estoy de acuerdo.** De lo contrario **No.**
![26  Confirmar el deshabilitado del producto](https://github.com/tupAlexLopez/system-management-products/assets/166257002/5005bfed-d507-4b22-a769-4ab2598eb12c)

##### La vista se actualizara y en la columna **Disponible** se visualizara una **X** indicando que el producto ya no se encuentra disponible.
![27  Visualizacion del producto deshabilitado](https://github.com/tupAlexLopez/system-management-products/assets/166257002/eb8d5cdd-63b3-4bf7-98b0-ca2b8a3d6ff6)

##### Si desea habilitar un producto, debe realizar el mismo proceso pero esta vez, la ventana te indicara si deseas **Habilitar el producto**.
![25  Click al boton de deshabilitar o habilitar producto](https://github.com/tupAlexLopez/system-management-products/assets/166257002/8cf68879-6041-4be7-97db-4405c422a543)

![26  Confirmar habilitacion del producto](https://github.com/tupAlexLopez/system-management-products/assets/166257002/75d29de4-1fdc-4f1b-b0cf-7844e1981ec0)

##### La vista se actualizara y podra visualizar que ahora la columna **Disponible** contiene un **✓** indicando que el producto esta disponible.
![27  Visualizacion del producto habilitado](https://github.com/tupAlexLopez/system-management-products/assets/166257002/92d1b395-f131-45f4-b83d-19d171f9869b)
---

#### ★ Eliminar producto existente

##### Click al boton
![28  Click al boton de eliminar producto](https://github.com/tupAlexLopez/system-management-products/assets/166257002/b707a884-b5ec-4af2-87a0-e439059699df)

#### Si realmente desea eliminar el producto, debe confirmar haciendo click al boton **Si, estoy de acuerdo.*** De lo contrario **No**.
![29  Confirmar eliminacion del producto](https://github.com/tupAlexLopez/system-management-products/assets/166257002/d78fdb69-a484-461b-953a-4f6686b30b33)

#### Vista de la Administracion cuando existen muchos productos. 

**La aplicacion cuenta con paginacion lo que significa que, si el listado de productos sobrepasa los 5 productos, esos productos se almacenaran en la pagina siguiente.**

![30  Administracion de productos con muchos productos](https://github.com/tupAlexLopez/system-management-products/assets/166257002/d1c38922-6f34-4028-8e5e-b79f49520621)
---
#### Filtrado y busqueda de Productos

#### ★ Filtrar por categoria
##### Click al boton
![25  Click al boton de filtrar por categoria](https://github.com/tupAlexLopez/system-management-products/assets/166257002/fc59ace0-b156-47b2-bf07-1701cfd36449)

##### Seleccione alguna categoria.
![31  Click a una de las opciones para filtrar  categorias](https://github.com/tupAlexLopez/system-management-products/assets/166257002/a4c5e85f-070d-4e8e-8d61-1bf723dc09e9)

#### El listado de productos se actualizara y podra visualizar el filtrado por la categoria seleccionada.
![32  Administracion por filtrado de categorias](https://github.com/tupAlexLopez/system-management-products/assets/166257002/686f8fe5-ab02-4882-8a15-87937c8cebf7)

![33  Administracion por filtrado de categorias #2](https://github.com/tupAlexLopez/system-management-products/assets/166257002/2d735b17-d3d9-4e08-adc9-107352590340)
---

#### ★ Filtrar por Disponibilidad.
##### Click al boton
![34  Click al boton de filtrar por Disponibilidad](https://github.com/tupAlexLopez/system-management-products/assets/166257002/3a31cd8f-ee1a-4140-bef4-28761f4ffc7a)
##### Seleccione alguna de las opciones disponibles.
![35  Click al boton de Disponible](https://github.com/tupAlexLopez/system-management-products/assets/166257002/52f4fd96-0720-4270-a055-7acaa4cfecd5)
#### El listado de productos se actualizara y podra visualizar el filtrado por la Disponibilidad seleccionada.
![36  Administracion por filtrado de disponibilidad](https://github.com/tupAlexLopez/system-management-products/assets/166257002/f3c698e6-68c5-4c10-b19a-f5812c035788)

![37  Click al boton de No Disponible](https://github.com/tupAlexLopez/system-management-products/assets/166257002/c2c23330-670e-4188-8db6-ba727eb5e8e8)

![38  Administracion por filtrado de No Disponible](https://github.com/tupAlexLopez/system-management-products/assets/166257002/318ba937-c4ce-47a0-9e8b-a56ed05c3ce3)
---

#### ★ Filtrar por categoria y disponibilidad
##### Podemos utilizar la combinacion de ambos filtros. Es decir por categoria y disponibilidad como se muestra en la imagen
![39  Click a opcion de categoria](https://github.com/tupAlexLopez/system-management-products/assets/166257002/5f452a8b-7b4e-4d50-807e-2b25c79bf2e6)

![40  Visualizacion del filtrado por categoria y disponibilidad](https://github.com/tupAlexLopez/system-management-products/assets/166257002/e87ed0d0-a0f6-4850-9bf9-60cac8119153)
---

#### ★ Filtrar por Descripcion
##### Escriba en el buscador alguna descripcion de un producto existente

**Podemos observar que cuenta con un autocompletado para mejorar y hacer mas precisas las busquedas.**

![41  Escribimos algun nombre de producto](https://github.com/tupAlexLopez/system-management-products/assets/166257002/17ecf78c-361e-4124-bbc7-3665b38ba0fb)

![41  Escribimos algun nomre de producto #2](https://github.com/tupAlexLopez/system-management-products/assets/166257002/cc7be184-deba-4f5e-8b72-837f957ffcd3)

##### Para realizar la busqueda debe apretar la  tecla **Enter** o **elegir una opcion que brinda el autocompletado**.

**El listado de productos se actualizara y se aplicara el filtrado por el texto que se encuentra en la busqueda.**

![42  Administracion por filtrado de descripcion de producto](https://github.com/tupAlexLopez/system-management-products/assets/166257002/3f17422e-dfcb-4dc5-b5df-97f08f675bf2)
---

#### ★ Filtrar por Descripcion, Categoria y Disponibilidad
##### Puede aplicar los tres filtros que existen en la aplicacion, es decir que puede filtrar por la descripcion, categoria y disponibilidad de un producto al mismo tiempo.
![44  Administracion por filtrado de descripcion y categoria y disponibilidad- Disponible](https://github.com/tupAlexLopez/system-management-products/assets/166257002/a4cb5a19-3c06-4c19-863c-a6278b95cd69)

![44  Administracion por filtrado de descripcion y categoria y disponibilidad- No disponible](https://github.com/tupAlexLopez/system-management-products/assets/166257002/c172fe50-73ec-4316-9bd2-52fddc14f848)

![43  Administracion por filtrado de descripcion y categoria](https://github.com/tupAlexLopez/system-management-products/assets/166257002/4eb9d142-b5e9-41cc-b4d0-4b46b70971c5)
---------