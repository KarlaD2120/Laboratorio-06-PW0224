# Preguntas teóricas

1. **¿Cuál es el propietario del servicio addNewUser?**
   
   R// El propietario del servicio **`addNewUser`** es el archivo **`user.service.js`**. Este servicio se encarga de recibir la información de un nuevo usuario y enviarla al modelo correspondiente para que sea almacenada en la base de datos. Además, devuelve el usuario ya almacenado.
2. **¿Para qué se utiliza res.render[ ] en los controladores?**
   
    La función **`res.render`** en los controladores de una aplicación web se utiliza para **renderizar vistas** y enviar el HTML resultante al cliente. Aquí tienes los puntos clave:

    - **Renderización de vistas**: Convierte una plantilla (como EJS, Pug, etc.) en HTML.
    - **Inyección de datos**: Permite pasar datos dinámicos a la vista para personalizar el contenido.
    - **Respuesta al cliente**: Envía el HTML generado como respuesta al navegador del usuario.

3. **¿Qué datos se envían a la vista home.pug desde el controlador addUserController?**

    El controlador **addUserController** envía los siguientes datos a la vista **home.pug**:
  
    - **Usuario**: Un objeto que contiene la información del nuevo usuario, incluyendo **name**, **lastname**, y **email**. Este objeto se crea y se guarda utilizando el servicio **addNewUser**.

