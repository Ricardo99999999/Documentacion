# Apuntes de código

## ¿Qué cosas he aprendido?

1. Hay cosas que no se pueden añadir en la clase main. Por ejemplo, clases abstractas no se pueden añadir en el main. Una clase static creo que tampoco.
2. Para la extracción de un fichero XML se utiliza la dependencia DOM.
3. Para la extracción de un fichero JSON se utiliza la librería Jackson.
   1. Recuerda que si utilizas un inputStream, la variable se instancia para abrir el buffer y luego se cierra, tendrás que instancias otra variable si no lo has guardado correctamente.
   2. Recuerda que se utilizan para manipular JSON. 
4. **Instanciar** : Es cuando se hace X = new X  ,  y se utiliza para crear el objeto. Una vez instanciado, se llama al constructor para inicializarlo.
5. **Constructor** : Es cuando se utiliza un método para inicializar un objeto
6. Las clases estáticas no se cambian y se pueden utilizar directamente desde cualquier lugar 
7. Las clases públicas también se puede utilizar desde cualquier lugar, únicamente es necesario la realización de un constructor. 
8. La clase enum sirve para proporcionar valores a ciertos datos.
9. Si queremos instancias un array siempre se debe de poner las dimensiones String [] names = new names [dimension];
10. Si no lo queremos dimensionar, hay que utilizar una arrayList <String> lista = new ArrayList<>();
11. Se utiliza FileWriter para escribir en ficheros.
12. Se utiliza el tipo inputStream para recoger datos de un buffer. Es importante que cuando se recojan los datos, le buffer se cierra, por lo que se deberá de guardar esta info en una variable.
13. Los get y set se utiliza dentro de una clase para que no pueda acceder cualquiera a la misma.
14. Las interfaces se utilizan para obligar a que una clase tenga una estructura determinada. Para poder utilizar una clase se utiliza la sentencia extends
15. La sentencia override se utiliza en las interfaces para quedarse con el valor de la última  clase.
16. El finally se utiliza para añadirle el valor final a dicha variable.