<h1 align="center">J.P.Q.L.</h1>
<p>J.P.Q.L. (Java Persistence Query Language) es el lenguaje de consultas que se utiliza en JPA (Java Persistence API) y Hibernate para interactuar con bases de datos relacionales. Es similar a SQL (Structured Query Language), pero está orientado a objetos, lo que significa que opera sobre entidades de Java en lugar de directamente sobre las tablas de la base de datos.</p>
<h2>Características principales de JPQL:</h2>

- <b>Consultas orientadas a objetos</b>: A diferencia de SQL, JPQL utiliza las entidades de Java como base, lo que permite realizar consultas sobre las clases y sus atributos en lugar de hacerlo sobre las tablas y columnas de la base de datos. Las relaciones entre entidades, como asociaciones `@OneToMany` o `@ManyToOne`, también pueden ser consultadas fácilmente.
- <b>Sintaxis basada en SQL</b>: Aunque orientado a objetos, la sintaxis de JPQL se basa en SQL, lo que lo hace familiar para los desarrolladores que ya conocen SQL. Soporta operaciones como `SELECT`, `INSERT`, `UPDATE`, y `DELETE`.
- <b>Independiente del proveedor de base de datos</b>: JPQL es un estándar dentro de JPA, lo que significa que es independiente del motor de base de datos que estés utilizando. Las consultas JPQL se traducen a SQL específico por el proveedor de persistencia, como Hibernate.

<h2>Diferencias entre JPQL y SQL:</h2>

- <b>JPQL</b> trabaja con <b>entidades y sus atributos</b>, mientras que <b>SQL</b> trabaja directamente con las <b>tablas y columnas</b>.
- JPQL es <b>agnóstico del proveedor de base de datos</b>. No requiere saber el dialecto SQL específico que usa el sistema de gestión de bases de datos.
- JPQL permite realizar consultas sobre <b>relaciones entre entidades</b>, utilizando directamente las asociaciones que se modelan en las clases Java.

<h2>Ventajas de usar JPQL:</h2>

- <b>Portabilidad</b>: Al ser independiente de la base de datos, puedes cambiar de proveedor de base de datos sin modificar las consultas JPQL.
- <b>Facilidad de uso</b>: Permite trabajar con objetos Java de manera natural, sin necesidad de preocuparse por la estructura de la base de datos.
- <b>Interacción con JPA</b>: Está diseñado para integrarse fácilmente con JPA y manejar las relaciones entre entidades Java de forma eficiente.
