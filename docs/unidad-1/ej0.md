# Proyecto tecnológico: Sistema de aviso para una puerta
Veamos un ejemplo de lo que sería un ejemplo de un proyecto tecnológico y los pasos que seguimos

## Situación de partida

En el instituto se quiere crear un pequeño sistema que **avise cuando una puerta queda abierta**.

El sistema tendrá una estructura que represente la puerta y utilizará una **placa micro:bit programada con MakeCode**.

Cuando se detecte que la puerta está abierta, el sistema mostrará un aviso mediante la matriz de LED de la micro:bit y/o emitirá un sonido. Cuando la puerta esté cerrada, el aviso desaparecerá.

Este proyecto permite trabajar:

- El proceso tecnológico.
- Estructuras.
- Materiales.
- Madera y metales.
- Mecanismos.
- Electricidad y electrónica.
- Programación.
- MakeCode.
- Hardware y software.
- Seguridad digital.
- Expresión gráfica.

---

# Correspondencia con los pasos para planificar y desarrollar un proyecto

| Paso | ¿Qué tendríamos que hacer en el proyecto? | Producto o evidencia |
|---|---|---|
| **1. Identificar la necesidad o problema** | Detectar que una puerta puede quedarse abierta y nadie darse cuenta. Investigar por qué puede ser un problema. | Descripción del problema |
| **2. Definir los objetivos** | Establecer qué debe conseguir el sistema: detectar la puerta abierta y avisar al usuario. | Lista de objetivos |
| **3. Generar y seleccionar ideas** | Pensar diferentes soluciones: LED, sonido, mensaje en micro:bit, sistema mecánico, etc. Comparar ventajas e inconvenientes y elegir una. | Tabla de ideas y elección |
| **4. Diseñar la solución** | Realizar un boceto de la puerta, la estructura y la colocación de la micro:bit. Diseñar también el funcionamiento mediante un diagrama de flujo. | Boceto + esquema + diagrama de flujo |
| **5. Planificar las tareas** | Dividir el trabajo: construir la estructura, preparar materiales, programar, montar, probar y documentar. | Lista de tareas y responsables |
| **6. Identificar los recursos** | Determinar materiales y herramientas: cartón, madera, pegamento, micro:bit, cables, elementos electrónicos, ordenador y MakeCode. | Lista de materiales y herramientas |
| **7. Organizar los tiempos** | Establecer cuánto tiempo se dedicará a diseñar, construir, programar, probar y presentar. | Cronograma o diagrama de Gantt |
| **8. Construir y desarrollar** | Construir la maqueta de la puerta y desarrollar el programa en MakeCode. | Prototipo + programa |
| **9. Probar y evaluar** | Comprobar diferentes situaciones: puerta cerrada, puerta abierta, errores de funcionamiento, etc. | Tabla de pruebas |
| **10. Mejorar** | Modificar la estructura o el programa si algo no funciona. Volver a probar. | Versión mejorada del prototipo |
| **11. Documentar y comunicar** | Recoger todo el proceso y presentar el proyecto al resto de la clase. | Memoria + exposición |

---

# 1. Identificar la necesidad o el problema
Partimos de la siguiente situación:

> **En algunas aulas, las puertas pueden quedar abiertas cuando no deberían. Esto puede provocar molestias, pérdida de climatización o problemas de seguridad. Se necesita un sistema sencillo que avise cuando la puerta esté abierta.**

### Preguntas que debemos hacernos

- ¿Cuál es el problema?
- ¿A quién afecta?
- ¿Dónde se produce?
- ¿Por qué sería útil solucionarlo?
- ¿Qué consecuencias puede tener no solucionar el problema?

### Producto final de esta fase

Una breve descripción de la necesidad o problema que se quiere resolver.

---

# 2. Definir los objetivos

Los objetivos del proyecto podrían ser:

1. Construir una pequeña maqueta de una puerta.
2. Diseñar un sistema capaz de detectar si la puerta está abierta.
3. Programar la micro:bit mediante **MakeCode o C o Java u otro lenguaje de programación**.
4. Mostrar un aviso cuando la puerta esté abierta.
5. Conseguir que el sistema sea sencillo, económico y fácil de utilizar.

Es importante que los objetivos sean **claros y comprobables**.

### Ejemplo

 ❌ Objetivo poco concreto:

> Hacer una puerta muy buena.

 ✅ Objetivo adecuado:

> Conseguir que el sistema avise cuando la puerta permanezca abierta.

---

# 3. Generar y seleccionar ideas

Cada grupo puede proponer diferentes soluciones.

### Posibles soluciones

#### Idea A

Un LED rojo se enciende cuando la puerta está abierta.

#### Idea B

La micro:bit muestra una `X` en su matriz LED y emite un sonido.

#### Idea C

La micro:bit muestra un mensaje como:

#### Idea D

Utilizar un pequeño mecanismo que active un interruptor cuando la puerta se abra.

---

## Comparación de ideas

| Solución | Ventajas | Inconvenientes |
|---|---|---|
| LED | Sencillo de construir y programar | Puede no ser suficientemente visible |
| Sonido | Llama la atención | Puede resultar molesto |
| Mensaje | Es muy claro para el usuario | Requiere más programación |
| Mecanismo | Permite trabajar mecanismos | Puede ser más complejo |

Finalmente, el grupo debe **seleccionar una solución y justificar su elección**.

---

# 4. Diseñar la solución

Antes de construir, debemos representar cómo será la solución.

## 4.1. Boceto

Realizar un dibujo de:

- La puerta.
- El marco.
- La micro:bit.
- El sistema de detección.
- Los elementos necesarios.

Ejemplo simplificado:

```text
        ┌──────────────────────┐
        │                      │
        │       PUERTA         │
        │                      │
        │             ┌──────┐ │
        │             │micro:│ │
        │             │ bit  │ │
        │             └──────┘ │
        │                      │
        └──────────────────────┘
``` 

## 4.2. Esquema

Representar cómo estarán conectados los componentes.

## 4.3. Diagrama de flujo

El funcionamiento puede representarse mediante:
```text

             INICIO
                │
                ▼
       Comprobar puerta
                │
                ▼
        ¿Está abierta?
          /          \
        SÍ            NO
        │              │
        ▼              ▼
 Mostrar aviso      No avisar
        │              │
        └──────┬───────┘
               │
               ▼
      Volver a comprobar
```

# 5. Planificar las tareas

El proyecto se puede dividir en diferentes tareas para organizar mejor el trabajo del equipo.

### Ejemplo de distribución de tareas

| Tarea | Responsable principal |
|---|---|
| Diseño y dibujo técnico | Alumno/a 1 |
| Construcción de la estructura | Alumno/a 2 |
| Programación en MakeCode | Alumno/a 3 |
| Montaje y conexiones | Alumno/a 4 |
| Realización de pruebas | Todo el equipo |
| Documentación del proyecto | Todo el equipo |
| Presentación del proyecto | Todo el equipo |

> **Importante:** aunque cada alumno tenga una responsabilidad principal, todos los miembros del equipo deben participar y conocer las diferentes fases del proyecto.

### Tareas que debe realizar el equipo

1. Analizar el problema y definir los objetivos.
2. Buscar y proponer diferentes soluciones.
3. Seleccionar la mejor solución.
4. Realizar los bocetos y esquemas.
5. Preparar los materiales y herramientas.
6. Construir la maqueta.
7. Programar la micro:bit con MakeCode.
8. Realizar el montaje.
9. Probar el funcionamiento.
10. Detectar y corregir errores.
11. Documentar el proceso.
12. Preparar la presentación final.

---

# 6. Identificar los recursos

Antes de comenzar la construcción debemos determinar qué recursos necesitamos para desarrollar el proyecto.

## Materiales

- Cartón, madera u otros materiales reciclados.
- Pegamento.
- Cinta adhesiva.
- Micro:bit. 
- Cables.
- Elementos electrónicos necesarios.
- Material para construir la puerta.
- Otros materiales necesarios para construir el mecanismo de detección.

## Herramientas

- Tijeras.
- Regla.
- Lápiz.
- Cutter, si procede y bajo supervisión.
- Pistola de pegamento, si se utiliza.
- Ordenador.

## Componentes electrónicos

Dependiendo de la solución elegida, podemos utilizar:

- Micro:bit.
- Pulsadores.
- Interruptores.
- LEDs.
- Cables.
- Sensores.
- Otros componentes necesarios.

## Software

- **MakeCode, C, J...**, para programar la micro:bit.

## Otros recursos

También debemos tener en cuenta:

- El espacio de trabajo.
- Los conocimientos necesarios.
- La información que necesitamos buscar.
- El presupuesto disponible, si fuera necesario.
- Las normas de seguridad del aula-taller.

### Clasificación de los recursos

| Tipo de recurso | Ejemplos |
|---|---|
| **Materiales** | Madera, cartón, plástico, pegamento |
| **Herramientas** | Tijeras, regla, cutter |
| **Componentes** | Micro:bit, cables, sensores, LED |
| **Software** | MakeCode,, C, J... |
| **Espacio** | Aula-taller |
| **Conocimientos** | Electricidad, estructuras, mecanismos y programación |
| **Recursos económicos** | Presupuesto disponible para comprar materiales |

> **Idea clave:** antes de comenzar a construir, debemos saber **qué necesitamos, qué tenemos disponible y qué nos falta**.

# 7. Organizar los tiempos

Una vez definidas las tareas y los recursos necesarios, debemos organizar el tiempo disponible para realizar el proyecto.

Se propone desarrollar el proyecto en **5 sesiones**.

### Planificación temporal

| Sesión | Tareas principales |
|---|---|
| **Sesión 1** | Analizar el problema, definir los objetivos y generar ideas. Seleccionar la solución. |
| **Sesión 2** | Realizar los bocetos, esquemas y planos. Preparar los materiales y herramientas. |
| **Sesión 3** | Construir la estructura de la puerta y preparar el mecanismo de detección. |
| **Sesión 4** | Montar los componentes electrónicos y programar la micro:bit con MakeCode. |
| **Sesión 5** | Probar el sistema, corregir errores, realizar mejoras y preparar la documentación y presentación. |

### Ejemplo de calendario

| Tarea | S1 | S2 | S3 | S4 | S5 |
|---|:---:|:---:|:---:|:---:|:---:|
| Analizar el problema | ✓ | | | | |
| Definir objetivos | ✓ | | | | |
| Generar y seleccionar ideas | ✓ | | | | |
| Diseño y planos | | ✓ | | | |
| Preparar materiales | | ✓ | | | |
| Construcción | | | ✓ | | |
| Montaje electrónico | | | ✓ | ✓ | |
| Programación con MakeCode | | | | ✓ | |
| Pruebas | | | | ✓ | ✓ |
| Mejoras | | | | | ✓ |
| Documentación | | | | | ✓ |
| Presentación | | | | | ✓ |

> **Idea clave:** una buena planificación del tiempo permite organizar el trabajo, evitar retrasos y conseguir que el proyecto esté terminado dentro del plazo previsto.

---

# 8. Construir y desarrollar

En esta fase llevamos a la práctica la solución que hemos diseñado.

El equipo debe seguir los planos y la planificación realizada anteriormente, trabajando de forma ordenada y respetando las normas de seguridad.

### 8.1. Construcción de la estructura

1. Preparar los materiales necesarios.
2. Medir y marcar las piezas según el diseño.
3. Cortar las piezas con las herramientas adecuadas.
4. Montar la estructura de la puerta.
5. Comprobar que la puerta puede abrirse y cerrarse correctamente.
6. Reforzar las partes que sean necesarias.

### 8.2. Construcción del mecanismo de detección

Se debe instalar un mecanismo que permita detectar si la puerta está abierta o cerrada.

Por ejemplo:

- Un pulsador.
- Un interruptor.
- Un sistema mecánico que active un contacto.
- Otro sistema de detección elegido por el equipo.

El mecanismo debe estar colocado de manera que cambie de estado cuando la puerta se abra o se cierre.

### 8.3. Montaje de los componentes electrónicos

Se conectan los componentes necesarios para que la micro:bit pueda detectar el estado de la puerta y emitir el aviso.

Por ejemplo:

- **Micro:bit** como elemento de control.
- **Pulsador o interruptor** para detectar la posición de la puerta.
- **LED o matriz de LEDs** para mostrar el aviso.
- **Zumbador**, si se ha elegido una señal acústica.
- **Cables** para realizar las conexiones.

> **Importante:** las conexiones deben realizarse con cuidado y siguiendo el esquema diseñado previamente.

### 8.4. Programación con MakeCode

La micro:bit se programa utilizando **MakeCode**.

El programa debe conseguir que:

- Cuando la puerta esté **cerrada**, no se active la alarma.
- Cuando la puerta esté **abierta**, se active un aviso.
- El aviso desaparezca cuando la puerta vuelva a cerrarse.

Un posible funcionamiento sería:

```text
INICIO
  ↓
Comprobar estado de la puerta
  ↓
¿La puerta está abierta?
  ├── SÍ → Mostrar aviso / activar alarma
  │
  └── NO → No mostrar aviso
  ↓
Volver a comprobar
```

### 8.5. Integración del sistema

Una vez construida la estructura, instalado el mecanismo y programada la micro:bit, se deben integrar todos los elementos para comprobar que funcionan conjuntamente.

El equipo debe realizar las siguientes comprobaciones:

1. Comprobar que la puerta se abre y se cierra correctamente.
2. Comprobar que el mecanismo detecta correctamente la posición de la puerta.
3. Verificar que la micro:bit recibe la información del mecanismo.
4. Comprobar que el programa de MakeCode responde correctamente.
5. Verificar que el aviso se activa cuando la puerta está abierta.
6. Comprobar que el aviso desaparece cuando la puerta se cierra.
7. Realizar varias pruebas para asegurarse de que el sistema funciona de forma fiable.

### Prueba básica de funcionamiento

| Estado de la puerta | Mecanismo | Micro:bit | Aviso |
|---|---|---|---|
| Cerrada | No activado | Detecta puerta cerrada | No |
| Abierta | Activado | Detecta puerta abierta | Sí |
| Cerrada de nuevo | No activado | Detecta puerta cerrada | No |

> **Idea clave:** todos los elementos del proyecto deben funcionar como un único sistema. Si alguna parte falla, debemos identificar el problema antes de continuar con la siguiente fase.

# 9. Probar y evaluar

Una vez construido y montado el sistema, debemos comprobar que funciona correctamente y que cumple los objetivos que habíamos definido al principio del proyecto.

Para ello, realizaremos diferentes pruebas en distintas situaciones.

### 9.1. Pruebas de funcionamiento

| Prueba | Situación | Resultado esperado | Resultado obtenido |
|---|---|---|---|
| 1 | Puerta cerrada | No se activa el aviso | |
| 2 | Abrimos la puerta | Se activa el aviso | |
| 3 | Cerramos la puerta | El aviso desaparece | |
| 4 | Abrimos y cerramos rápidamente | El sistema responde correctamente | |
| 5 | Repetimos varias veces | El sistema funciona de forma fiable | |

### 9.2. Evaluación del funcionamiento

Después de realizar las pruebas, debemos analizar los resultados y comprobar si el proyecto cumple los objetivos.

Podemos responder a las siguientes preguntas:

- ¿La puerta se abre y se cierra correctamente?
- ¿El mecanismo detecta correctamente cuándo la puerta está abierta?
- ¿La micro:bit recibe correctamente la información?
- ¿El programa realizado con MakeCode funciona como esperábamos?
- ¿El aviso se activa cuando la puerta está abierta?
- ¿El aviso desaparece cuando la puerta se cierra?
- ¿El sistema funciona correctamente después de repetir varias veces la prueba?
- ¿La estructura es estable y resistente?
- ¿Las conexiones eléctricas son correctas y seguras?

### 9.3. Detección de errores

Si el sistema no funciona correctamente, debemos intentar localizar el origen del problema.

| Problema | Posible causa | Posible solución |
|---|---|---|
| No se activa el aviso | El mecanismo no detecta la apertura | Revisar el mecanismo y sus conexiones |
| El aviso permanece activado | El programa no detecta el cierre | Revisar el programa en MakeCode |
| La micro:bit no responde | Existe un problema en las conexiones | Revisar los cables y componentes |
| La puerta no se mueve bien | Problema en la estructura o mecanismo | Ajustar o reforzar las piezas |
| El sistema funciona de forma irregular | El mecanismo no está bien colocado | Ajustar la posición del mecanismo |

### 9.4. Conclusión de la evaluación

Al finalizar las pruebas, el equipo debe indicar:

- **Qué funciona correctamente.**
- **Qué problemas se han encontrado.**
- **Qué cambios se han realizado.**
- **Qué aspectos podrían mejorarse.**
- **Si se han cumplido los objetivos iniciales.**

> **Idea clave:** probar y evaluar nos permite comprobar si nuestra solución funciona realmente y detectar los problemas que debemos corregir antes de dar el proyecto por terminado.

# 10. Mejorar

Después de realizar las pruebas y evaluar el funcionamiento del proyecto, debemos realizar las mejoras necesarias para solucionar los problemas detectados.

La finalidad de esta fase es conseguir que la solución tecnológica funcione de la mejor manera posible.

### 10.1. Propuesta de mejoras

Según los resultados obtenidos en las pruebas, podemos realizar diferentes modificaciones:

| Problema detectado | Mejora propuesta |
|---|---|
| La puerta no se mueve correctamente | Ajustar o modificar la estructura |
| El mecanismo no detecta siempre la apertura | Cambiar su posición o mejorar el mecanismo |
| El aviso no se activa correctamente | Revisar las conexiones y el programa |
| El aviso tarda demasiado en aparecer | Modificar el programa en MakeCode |
| La estructura es poco resistente | Reforzar las piezas |
| Los cables se desconectan | Fijar mejor las conexiones |
| El aviso no es suficientemente visible | Cambiar o mejorar la señal luminosa |
| El aviso acústico es demasiado débil | Ajustar o sustituir el sistema de aviso |

### 10.2. Proceso de mejora

Para mejorar el proyecto seguiremos estos pasos:

1. Identificar los problemas encontrados durante las pruebas.
2. Analizar las posibles causas.
3. Proponer diferentes soluciones.
4. Seleccionar la mejora más adecuada.
5. Realizar los cambios necesarios.
6. Volver a probar el sistema.
7. Comprobar si la mejora ha solucionado el problema.
8. Registrar los cambios realizados.

### 10.3. Registro de mejoras

| Problema | Mejora realizada | ¿Ha funcionado? |
|---|---|---|
| | | |
| | | |
| | | |

### 10.4. Evaluación final de las mejoras

Una vez realizadas las modificaciones, debemos comprobar nuevamente que:

- La estructura es estable y resistente.
- La puerta funciona correctamente.
- El mecanismo detecta la apertura y el cierre.
- Las conexiones eléctricas funcionan correctamente.
- El programa de **MakeCode** responde adecuadamente.
- El aviso se activa cuando la puerta está abierta.
- El sistema funciona correctamente después de repetir las pruebas.

> **Idea clave:** un proyecto tecnológico casi nunca funciona perfectamente a la primera. **Probar, detectar errores y mejorar** forma parte del proceso tecnológico.

# 11. Documentar y comunicar

Una vez terminado el proyecto, debemos recoger y organizar toda la información sobre el proceso seguido y comunicar el resultado al resto de la clase.

La documentación debe mostrar **qué problema hemos intentado solucionar, cómo lo hemos hecho, qué dificultades hemos encontrado y cómo las hemos solucionado**.

### 11.1. Documentación del proyecto

El equipo elaborará un documento que incluya los siguientes apartados:

1. **Título del proyecto**
2. **Problema o necesidad detectada**
3. **Objetivos del proyecto**
4. **Ideas propuestas y solución seleccionada**
5. **Bocetos, planos y esquemas**
6. **Materiales, herramientas y componentes utilizados**
7. **Planificación de las tareas y los tiempos**
8. **Proceso de construcción**
9. **Programación realizada con MakeCode**
10. **Pruebas realizadas y resultados obtenidos**
11. **Problemas encontrados**
12. **Mejoras realizadas**
13. **Resultado final**
14. **Conclusiones**

### 11.2. Evidencias del proceso

Durante el desarrollo del proyecto se pueden recoger diferentes evidencias:

- Fotografías de las diferentes fases de construcción.
- Bocetos y planos realizados.
- Esquemas de las conexiones.
- Capturas del programa realizado en MakeCode.
- Tabla de pruebas.
- Registro de los problemas y las soluciones aplicadas.
- Fotografías del prototipo terminado.

### 11.3. Comunicación del proyecto

Cada equipo realizará una breve presentación ante la clase para explicar su proyecto.

La presentación puede tener una duración aproximada de **3-5 minutos**.

Debe incluir:

- ¿Qué problema hemos detectado?
- ¿Qué solución hemos diseñado?
- ¿Cómo funciona nuestro sistema?
- ¿Qué materiales y componentes hemos utilizado?
- ¿Cómo hemos utilizado la micro:bit y MakeCode?
- ¿Qué problemas hemos encontrado?
- ¿Qué mejoras hemos realizado?
- ¿Cuál ha sido el resultado final?

### 11.4. Presentación del prototipo

Durante la exposición, el equipo deberá mostrar el prototipo y realizar una demostración de su funcionamiento.

Se debe comprobar que:

1. La puerta puede abrirse y cerrarse.
2. El mecanismo detecta correctamente su estado.
3. La micro:bit recibe la información.
4. El programa funciona correctamente.
5. El aviso se activa cuando la puerta está abierta.
6. El aviso desaparece cuando la puerta se cierra.

### 11.5. Conclusión

Al finalizar el proyecto, el equipo realizará una valoración final indicando:

- Qué hemos aprendido.
- Qué ha funcionado correctamente.
- Qué dificultades hemos tenido.
- Cómo hemos solucionado los problemas.
- Qué cambiaríamos si volviéramos a realizar el proyecto.

> **Idea clave:** documentar y comunicar permite explicar el proceso tecnológico seguido y demostrar cómo hemos pasado de un **problema inicial a una solución tecnológica**.
