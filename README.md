# Module 5: Creating a Class Hierarchy by Using Inheritance

## Lab: Refactoring Common Functionality into the User Class

1. **Nombres y apellidos:** Francisco Javier Moreno QUevedo
2. **Fecha:** 20/10/2020
3. **Resumen del Ejercicio:**  Creamos en la clase user el metodo SetPassword  y lo aplicamos en los forms y las clases student y teacher
4. **Dificultad o problemas presentados y como se resolvieron:** Ninguna



- Ejercicio 2: Implementing Password Complexity by Using an Abstract Method

  - Creamos el metodo SetPassword en la clase user 
  
  - Borramos el campo _password y lo sustituimos por protected string _password = Guid.NewGuid().ToString();
  
  - Creamos el metodo Setpassword en la clase  teacher y student ya que va a haber una complejidad de contraseña en cada uno de ellos
  
  - Habilitamos la funcionalidad del boton Change_Password.
  
    - Chequeamos la password
    - verificamos si los campos de password no son iguales
    - Verificamos que la password cumple con las restricciones
  
    
  
    

