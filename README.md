# XML-XSD-1stProject

      A partir de los archivos .xml, obtener los .xsd y añadiendole los siguientes apartados:
      
####  Ejercicio 1 (Solamente crear el ejercicio1.xsd normal a partir del ejercicio1.xml).

####  Ejercicio 2 (Crear el ejercicio2.xsd a partir del ejercicio2.xml y teniendo los siguientes puntos en cuenta):
      ● El elemento Year será un entero entre 1500 y 2022. Por defecto, tiene un valor de 2012 sólo
        puede aparecer una vez.
      ● El elemento Month tendrá un valor entre 01 y 12. Por defecto, tiene un valor de 12 y sólo puede
        aparecer una vez.
      ● El elemento Day tendrá un valor entre 01 y 31. Por defecto, tiene un valor de 12 y sólo puede
        aparecer una vez.
        
####  Ejercicio 3 (Crear el ejercicio3.xsd a partir del ejercicio3.xml y teniendo los siguientes puntos en cuenta):
      ● El elemento DateCompleted sólo puede aparecer una vez y sus hijos igual. Estos hijos
        deben seguir las restricciones del ejercicio 2.
      ● El elemento DateRevised sólo puede aparecer una vez y sus hijos igual. Estos hijos
        deben seguir las restricciones del ejercicio 2.
      ● El atributo Status es opcional y tiene un valor fijo que es MEDLINE.

####  Ejercicio 4 (Crear el ejercicio4.xsd a partir del ejercicio4.xml y teniendo los siguientes puntos en cuenta):
      ● El contenido del ISSN debe tener un patrón NNNN-NNNN donde N es un número entre 0 y 9.
      ● El atributo IssnType tiene un valor predeterminado Print y este atributo es no obligatorio.
      ● El elemento Month tiene por valor: Jan, Feb, Mar, Apr, May, Jun, Jul, Aug, Sep, Oct, Nov,
        Dec.
      ● El elemento PubDate tiene otro hijo llamado Day pero este elemento es opcional que
        aparezca.
      ● El elemento PubDate tiene tres hijos Year, Month y Day, pero pueden aparecer en cualquiera
        orden.
        
####  Ejercicio 5 (Crear el ejercicio5.xsd a partir del ejercicio5.xml y teniendo los siguientes puntos en cuenta):
      ● El elemento Author puede aparecer 100 veces como máximo, y mínimamente 1 vez.
      ● El atributo CompleteYN y el atributo ValidYN tiene un valor predeterminado que es Y.
      ● El elemento Author tiene un hijo que deja escoger entre LastName y SureName.
      ● El elemento ForeName tiene un contenido que sigue el patrón LSL (donde L=Lelltra y S=Espacio).
      ● El elemento Initials tiene un contenido que sigue el patrón LL (donde L=Lelltra).
      
####  Ejercicio 6 (Crear el ejercicio6.xsd a partir del ejercicio6.xml y teniendo los siguientes puntos en cuenta):
      ● El elemento Chemical puede aparecer infinitamente de golpes, y mínimamente 1 vez.
      ● El atributo UI sigue un patrón D00NNNN donde N tiene un valor entre 0 y 9.

####  Ejercicio 7 (Crear el ejercicio7.xsd a partir del ejercicio7.xml y teniendo los siguientes puntos en cuenta):
      ● Incluir todas las restricciones de los ejercicios anteriores.
