# Nombre de tu escena

Emergency Case

Allan Miranda Páez · Realidades Extendidas y Experiencias Inmersivas · UGM · 2026

## 1 · Qué es

Simulador de casos medicos, para estudiantes de medicina, con un objetivo de inmersión en que hacer según los casos que se presentan

- Palabra que busco transmitir: Educación

## 2 · Cómo se usa

- Enlace a la escena: https://allan-miranda-ugm.github.io/Emergency_case/
- Dispositivo pensado: computador / teléfono
- Al entrar: Iniciar seleccionando el primer caso, para ser transportado al primer escenario, al entrar es posible ver elementos para su interacción, la mas notable es una medalla giratoria con simbolo de ambulancia, al hacerle click, aparece el contexto de la escena, y la recomendación sobre el procedimiento, luego están los instrumentos medicos, estos deben usarse en orden correcto para poder aprobar el caso.

## 3 · Cómo está hecha

- Herramienta: A-Frame, publicado en GitHub Pages.
- Archivos que usé:

  - **activos/icono_ambulancia.glb**: modelo 3D. Origen: Poly.Pizza. Licencia: Gratis
  - **activos/IVfluid.glb**: modelo 3D. Origen: Poly.Pizza. Licencia: Gratis
  - **activos/jeringa.glb**: modelo 3D. Origen: Poly.Pizza. Licencia: Gratis
  - **activos/m_aventurero.glb**: modelo 3D. Origen: Poly.Pizza. Licencia: Gratis
  - **activos/male1.glb**: modelo 3D. Origen: Poly.Pizza. Licencia: Gratis
  - **activos/street.glb**: modelo 3D. Origen: Poly.Pizza. Licencia: Gratis
  - **activos/table_f.glb**: modelo 3D. Origen: Poly.Pizza. Licencia: Gratis
  - **activos/table_m.glb**: modelo 3D. Origen: Poly.Pizza. Licencia: Gratis
  - **activos/trees.glb**: modelo 3D. Origen: Poly.Pizza. Licencia: Gratis
  - **activos/bandage.glb**: modelo 3D. Origen: Poly.Pizza. Licencia: Gratis
  - **activos/bandage_r.glb**: modelo 3D. Origen: Poly.Pizza. Licencia: Gratis

  - **activos/ambient_city.mp3**: sonido de fondo. Origen: Pixabay.com. Licencia: CC0
  - **activos/ambient_forest.mp3**: sonido de fondo. Origen: Pixabay.com. Licencia: CC0
  - **activos/finish.mp3**: sonido al clic. Origen: Pixabay.com. Licencia: CC0
  - **activos/interact.mp3**: sonido al clic. Origen: Pixabay.com. Licencia: CC0
  - **activos/correcto_1.mp3**: sonido al clic. Origen: http://noproblo.dayjo.org/ZeldaSounds/. Licencia: CC0 
  - **activos/correcto_2.mp3**: sonido al clic. Origen: http://noproblo.dayjo.org/ZeldaSounds/. Licencia: CC0 
  - **activos/error.mp3**: sonido al clic. Origen: http://noproblo.dayjo.org/ZeldaSounds/. Licencia: CC0 

## 4 · Decisiones

- Decidi una iluminación que se asemeje a un ambiente nocturno, con sonidos que solo apoyen el impacto visual y que no distraigan al usuario, para que así haya mas enfoque en las tareas a la mano, las interacciones están a la vista y se permiten los errores las veces que sean necesarias.
- Eliminé el sistema de puntaje, para Destacar aun más el enfoque de ensayo y error que quiero darlo a mi proyecto

## 5 · Testing

Video del recorrido: https://youtu.be/Io01NVRmhoM

### Abrir el enlace en ventana privada
- Resultado: Posible desde el inicio

### Dispositivo elegido
- Resultado: Principalmente Computador
- Ajuste que hice: Interacciones desde los clicks del mouse y un espacio visual limpio

### Interacciones, una por una
- Resultado: Menú de inicio, cambio de escenas entre casos, objetos seleccionables que deben ser elegidos en un orden especifico, sistema de pistas contextuales a la mano para el usuario, una forma de dejar el caso por medio de un modelo de ambulancia, dependiendo de como se sale de la experiencia, termina en fallo (ambulancia), o en victoria (procedimientos con instrumentos medicos)

### Sonido con audífonos
- Resultado: Desde sonido de fondo hasta sonidos contextuales
- Ajuste que hice: Los sonidos de fondo suenan desde el momento que el usuario interactua con cualquier objeto, ya que al ser una experiencia web, debe tener el permiso del usuario para esto en el navegador, así que al hacer que suene desde la primera interacción, se puede omitir este paso

### Fluidez del recorrido
- Resultado: Fluidez lograda, usuario no se atora en el procedimiento medico
- Ajuste que hice: El sistema de pistas da pistas claras para seguir un procedimiento en especifico

### Entrar como si fuera la primera vez
- Resultado: La interfaz es clara y al punto
- Ajuste que hice: Un menú que solo tiene lo necesario y no ahoga visualmente

## 6 · Uso de IA

- La IA (Chat GPT) asistio en cuanto al uso de JavaScript en ciertas partes como por ejemplo el funcionamiento del menu principal, la transición entre escenas y la distribución random de arboles y el sistema de selecciones correctas.
- Hice la gran mayoria de los escenarios distribuyendo los modelos, hice el codigo principal fuera del JavaScript y además alteré el mismo codigo JavaScript para que el funcionamiento fuera especifico de lo que yo queria.

## 7 · Pendientes para el examen

- Arreglar los botones del menú principal, agregar más escenarios, agregar un menu de resultados y tambien que los casos varien en su metodo de completado
