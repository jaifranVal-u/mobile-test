# mobile-test
Gracias por continuar en el proceso de selección, estás a un paso más de entrar a ser parte del equipo de Val-u, a continuación verás en detalle los pasos a seguir para realizar el test para Jr Mobile Developer, lee con cuidado, si no quedó claro alguna de las instrucciones, dejanolas saber y te la aclararemos a lo largo de la evaluación

Los requerimientos para considerar completado el test son:

- Tienes que representar las siguientes 2 vistas, agregando el UI/UX de tu preferencia, tener en cuenta que las decisiones de diseños serán tomadas en cuenta por el equipo a la hora de hacer la evaluación del desafío técnico.
- Debes conectarte a una API mock creada específicamente para el test donde tendrás 4 endpoints
   - Estudiantes
   - Profesor
   - Módulo
   - Salón
   - La API http://valutest.pythonanywhere.com/
- Debes conectarte a la API, hacer un request y traerte la información que en ella obtendrás
- Debes dividir los estudiantes por:
  - Lista general
  - Modulos
  - Salones
- En el card list de éstas listas deberás colocar los siguientes datos de los estudiante
  - Nombre
  - Apellido
  - Salón al que pertenece
  - Módulo al que está inscrito
  - Y fecha formateada en la que ése estudiante fue creado
  - Y fecha de la última modificación que se le hizo al estudiante
- Luego, cada estudiante de ésa lista debe tener un view de perfil dinámico, cuyos datos van a cambiar según el estudiante al que se quiera consultar
- Dentro de la vista de perfil, queremos que los estudiantes tengan a su disposición, toda la información de la lista anterior, y además:
  - ID del estudiante
  - Cédula
  - Teléfono
  - Correo
- Nuestros estudiantes no poseen fotos de perfil, por ende, necesitamos que tengan una foto de perfil, para éso vamos a llamar a ésta API: https://randomuser.me/api/?inc=picture
  - Queremos que cada estudiante tenga una foto única almacenada en la app, y que sea la misma foto sin importar de donde se vea la información del estudiante
  - Cada estudiante debe tener ésa foto y ésta no debe cambiar si se consulta la vista de nuevo
  - Para lograr ésto se puede usar un state manager se puede usar memoria cache, eres libre de obtener el resultado mediante el método que se te sea más eficiente y adecuado.

Nuevamente, la disposición de toda ésta información queda a juicio del candidato, toda decisión de diseño, estrutura de los componentes, jerarquización de textos y relevancia de la información será evaluada por el equipo de Val-u.

Sin más nada que agregar, éxitos en el desafío, y esperamos que tú seas el candidato que estamos buscando para unirse a nuestro quipo

## PD: Los diseños low fidelity de referencia a continuación:

![Lista](https://github.com/jaifranVal-u/mobile-test/blob/main/prueba_pages-to-jpg-0001.jpg?raw=true)
![Perfil](https://github.com/jaifranVal-u/mobile-test/blob/main/prueba_pages-to-jpg-0002.jpg?raw=true)
