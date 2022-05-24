![image](https://user-images.githubusercontent.com/91554777/170103427-2b681a6e-05b6-49f3-834b-c188ebf12fbb.png)

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Formulario</title>
    </head>
    <h1>Realiza el siguiente Formulario</h1>
    <body>
        <h2>Formato de registro</h2>
        <form action="https://formspree.io/f/mzboodyj">
            <fieldset>
            <legend><strong>Infomacion Personal</strong></legend>
            <P><strong>Intrduce tu nombre completo</strong></P>
           <input type="text" name="Intrduce tu nombre completo">
           <P><strong>Intrduce tu email</strong></P>
           <input type="email" id="email" name="Intrduce tu email">
           <P><strong>Intrduce tu Contraseña</strong></P>
           <input type="password" id="password" name="Intrduce tu Contraseña" minlength="4" maxlength="8">
           <P><strong>Confirma tu Contraseña</strong></P>
           <input type="password" id="password" name="Confirma tu Contraseña" minlength="4" maxlength="8">

           <form>
            Genero: <br>
            <input type="radio" id="gender" name="gender" value="male"/>Masculino<br>
            <input type="radio" id="gender" name="gender" value="female"/>Femenino<br>
            <input type="radio" id="gender" name="gender" value="other"/>Otro 
        </form>

        <form>
            Ingresa tu dirección:<br>
            <textarea rows="5" cols="25"></textarea>
        </form> 
        <input type="submit" value="Enviar">
        </fieldset>
        </form>
    </body>
    </html>
