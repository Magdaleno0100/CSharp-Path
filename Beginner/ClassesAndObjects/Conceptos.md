
References Types

Es básicamente cuando la variable contine la dirección de memoria en lugar del valor.

Las clases son un ejemplo de este tipo.
Por ejemplo:

    GradeBook book = new GradeBook();
    book.AddGrade(91);
    book.AddGrade(65.2f);

Aquí la variable book que contiene el objeto creado, en realidad no guarda el valor o los valores que se están agregando, si no que guarda la dirección de memoria en donde se están almacenando estos datos.
A continuación creamos una nueva variable y le asignamos la dirección de memoria del objeto creado en la varibale book, por lo que al agregar un nuevo valor con el método AddGrade, lo estamos haciendo sobre la primera dirección de memoria.

    GradeBook book2 = book;
    book2.AddGrade(80);




Access Modifiers

