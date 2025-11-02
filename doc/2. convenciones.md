### Anotaciones
En SpringBoot, una anotacion se utiliza para configurar y definir el comportamiento de los componentes de una aplicaicon.

Estas anotaciones se utilizan en conjunto con Spring Framework para simplificar el desarrollo de aplicaciones empresariales java

La anotaciones se definen de la siguiente manera:
Debe iniciar por el simbolo de '@', seguido del nombre de la anotacion '@GetMapping'

@GetMapping("/clientes") anotacion con atributo String.

Anotaciones principales

- @SpringBootAplication: (Clase principal) Anotacion principal que se utiliza para marcar la clase principal de una aplicacion Spring boot.

- @RestController: La anotacion @RestController se utiliza para marcar una clase Java como un controlador REST, en un aplicacion Spring Boot.
Esta anotacion combina las funcionalidades de @Controller y @ResponseBody, lo que significa que es capaz de manejar solicitudes HTTP y devolver datos directamente en formato JSON o XML.
En esencia, @RestController se utiliza para crear controladores en aplicaciones Spring Boot que generan respuestas HTTP para APIs RESTFULL

Cuando una clase esta anotada con @RestController, cada metodo de esa clase se mapea automaticamente a una ruta URL y responde a las solicitudes HTTP entrantes en funcion de las anotaciones: @GetMapping, @PostMapping, @PutMapping, @DeleteMapping, etc.

- @GetMapping: Se utiliza para mapear las solicitudes HTTP GET a metodos de controlador especificos en una aplicacion Spring boot.
Esta anotacion se utiliza comunmente en combinacion con la anotacion @RestController o @Controller para crear controladores RESTFULL en una aplicaicon Spring.

Cuando se tiliza @GetMapping, Spring Boot asigna la URL especificada en la anotacion a un metodo en el controlador y maneja automaticamente las solicitudes HTTP GET que llegan a esas URL, invocando el metodo correspondiente y devolviendo el resultado como respuesta.