# Lab 10

## Desarrollo

1documentos 
![img1](img/vista_documentos.PNG)
2agregar documento
![img2](img/vista_contacto_agregar.PNG)
3Autocompletado de nombre dependiendo del DNI o RUC
![img3](img/GIF_prueba_DNI_RUC.gif)
4Editando un documento
![img4](img/GIF_editando.gif)
5Evitando un duplicado de contactos
![img5](img/GIF_duplicado_contactos.gif)
6Estado los campos relacionados en una factura
![img6](img/GIF_campos_relacionados.gif)
## Conclusiones

- Al trabajar con una API nos facilita algunos procesos, pero no debemos depender muhco de servicos fuera de nuestro alcanse.
- Para  obtener la data primeramente necesitamos el token y el url  base , seguidamente ejecutamos la funcion get_doc y validamos si la peticion fue correcta o no.
- Antes de hacer la peticion de la informacion primeramente validamos si es dni o ruc,dependiendo de esto hacemos el filtrado de la data para obtener la data que requerimos.
- El metodo api.constrains nos permitio validar si el contacto que agregaremos no exista, con el metodo search_count la cual valida dependiendo de 3 parametros.

