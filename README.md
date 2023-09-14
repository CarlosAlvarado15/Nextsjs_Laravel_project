"# Nextsjs_Laravel_project" 
usuario:admin@admin.com
password:admin

Vista de Login. Desde el sidebar  Sign in.  Usuario por defecto admin@admin.com  password: admin.











Una vez logeado puede editar su perfil dirigiéndose al navbar perfil . 















Desde esta vista podrá ver su perfil y en el botón editar actualizar los campos requeridos.  














Todos los input funcionan menos el de la fotografía.  Una vez guardado se redirigirá a la vista perfil para ver sus campos actualizados. 












Desde el sidebar podrá seleccionar User y mostrara la siguiente tabla con los usuarios registrados. Y  sus respectivos roles.  En este caso el administrador por defecto es quien selecciona los roles. 

 

Desde la tabla de usuarios en la columna de operaciones se selecciona el botón editar y se actualizan  dicho campo, bien sea asignando un nuevo role o eliminado el actual.  










Desde el Navbar el administrador puede seleccionar registro y crear un nuevo usuario asignándole un correo y clave por predeterminado que este luego al logearse podrá actualizar  y de la misma manera actualizar su perfil.   .ejemplo. 

























usuario creado con éxito.  Se puede observar en la base de datos el nuevo usuario.  
para verificar en la tabla de usuario se dirigie a la tabla user y se mostrara un 2 donde se le podrá asignar un role














por supuesto que solo se muestra los campos vacíos ya que el usuario no se ha logeado y tampoco ha actualizado su perfil. Sin embargo se puede asignar los roles a ese determinando usuario.  






































ya una vez el administrador asigne el role que le corresponde. Podrá entregar las credenciales al nuevo usuario para que entre al sistema y actualice su perfil como se explico anteriormente.   

Repositorios del 
Backend: https://github.com/CarlosAlvarado15/backend4.git
Frontend: https://github.com/CarlosAlvarado15/septiembre4.git 


Para salir del sistema desde el Navbar selecciona Logout y podrá cerrar esa sesión. 


Hasta ahora esto fue lo que se pudo realizar en el tiempo.   
El Frontend fue realizado con Next.js  y el Backend con Laravel donde se  crearon las Api y el sistema de autenticación por token con sanctum. 


