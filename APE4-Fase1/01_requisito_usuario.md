# ☕ CaféU — Requisito del Usuario

**Actividad:** APE 4 — Fase 1  
**Asignatura:** Interacción Humano Computador (IHC)  
**Institución:** Universidad Técnica de Ambato — FISEI  
**Carrera:** Software  
**Proyecto:** CaféU — Sistema de pedidos para cafetería universitaria  
**Archivo:** `APE4-Fase1/01_requisito_usuario.md`

---

## 1. Descripción del problema

CaféU es una cafetería universitaria ficticia que atiende a estudiantes durante sus descansos académicos. En estos horarios suele existir una gran afluencia de personas, lo que puede generar filas, tiempos de espera prolongados y dificultades al momento de realizar un pedido.

Actualmente, un estudiante que desea comprar un producto debe acercarse a la cafetería, esperar su turno y comunicar verbalmente lo que necesita. Este proceso puede resultar incómodo cuando dispone de pocos minutos antes de regresar a clases.

Ante esta situación, surge la necesidad de diseñar una solución digital que permita realizar pedidos de manera rápida, sencilla y organizada, sin depender de una conversación verbal para seleccionar los productos.

## 2. Perfil del usuario objetivo

El usuario principal de CaféU es un estudiante universitario que necesita adquirir alimentos o bebidas durante sus descansos académicos.

| Característica | Descripción |
|---|---|
| **Tipo de usuario** | Estudiante universitario |
| **Edad referencial** | Entre 18 y 25 años |
| **Ocupación** | Estudiante de educación superior |
| **Conocimiento tecnológico** | Familiarizado con teléfonos inteligentes y aplicaciones digitales |
| **Dispositivo principal** | Teléfono celular |
| **Contexto de uso** | Cafetería universitaria durante los descansos |
| **Tiempo disponible** | Limitado debido a sus horarios de clases |
| **Necesidad principal** | Realizar un pedido sin tener que explicarlo verbalmente |
| **Dificultad actual** | Filas concurridas, esperas e incertidumbre sobre la recepción del pedido |
| **Expectativa** | Completar el pedido con pocos pasos y recibir una confirmación clara |

### Escenario del usuario

Un estudiante tiene un descanso entre clases y desea comprar un café americano y un sanduche. Debido a que la cafetería se encuentra concurrida, prefiere realizar su pedido desde el teléfono.

Al ingresar a CaféU, consulta el menú, selecciona los productos y revisa el siguiente resumen:

| Producto | Cantidad | Precio |
|---|:---:|---:|
| Café americano | 1 | $1,50 |
| Sanduche | 1 | $2,75 |
| **Total** | | **$4,25** |

Antes de confirmar, necesita comprobar que los productos, cantidades y precios sean correctos. Si encuentra algún error, debe poder editar su selección sin comenzar nuevamente todo el proceso.

Cuando confirma, espera visualizar un mensaje que indique claramente que su pedido fue recibido.

## 3. Requisito principal del usuario

**RU-01 — Realización y confirmación de pedidos digitales**

El sistema CaféU debe permitir que un estudiante universitario consulte el menú, seleccione productos, revise y modifique su pedido antes de confirmarlo y reciba una confirmación visual clara cuando el pedido haya sido recibido correctamente.

Este proceso debe ser sencillo, comprensible y adecuado para utilizarse desde un teléfono móvil durante un descanso académico.

### Necesidades del usuario

| Código | Necesidad | Descripción |
|---|---|---|
| NU-01 | Consultar el menú | Visualizar los productos disponibles con sus nombres y precios. |
| NU-02 | Seleccionar productos | Elegir uno o varios productos y establecer sus cantidades. |
| NU-03 | Revisar el pedido | Comprobar productos, cantidades, precios y total antes de confirmar. |
| NU-04 | Editar el pedido | Modificar cantidades, eliminar o agregar productos antes de la confirmación. |
| NU-05 | Confirmar el pedido | Disponer de una acción clara para enviar el pedido seleccionado. |
| NU-06 | Recibir confirmación | Visualizar un mensaje comprensible que indique que el pedido fue recibido. |
| NU-07 | Evitar errores | Poder corregir equivocaciones antes de confirmar la compra. |
| NU-08 | Ahorrar tiempo | Realizar el proceso con pocos pasos y sin necesidad de comunicar verbalmente los productos elegidos. |

## 4. Objetivo de la solución digital

### Objetivo general

Diseñar una solución digital para CaféU que permita a los estudiantes universitarios consultar el menú, seleccionar productos, revisar y editar sus pedidos, confirmarlos y recibir una respuesta clara sobre su recepción, facilitando una experiencia de interacción rápida, sencilla y comprensible.

### Objetivos específicos

1. **Facilitar la selección de productos** mediante un menú digital que presente información clara sobre los alimentos, bebidas y sus respectivos precios.

2. **Permitir la revisión y modificación del pedido** antes de su confirmación, mostrando los productos seleccionados, cantidades y total para prevenir errores.

3. **Proporcionar una confirmación visual comprensible** después del envío del pedido, para que el estudiante conozca si fue recibido correctamente.

## 5. Recorrido principal del usuario

El recorrido de CaféU contempla cinco etapas principales.

| Etapa | Pantalla o estado | Acción del usuario | Resultado esperado |
|---|---|---|---|
| 1 | Menú | Consulta los productos disponibles. | Visualiza productos y precios. |
| 2 | Selección | Elige un café americano y un sanduche. | Los productos se agregan al pedido. |
| 3 | Revisión | Comprueba los productos y el total de $4,25. | Visualiza el resumen y las opciones de editar o confirmar. |
| 4 | Confirmación | Presiona el botón «Confirmar pedido». | El sistema procesa el envío y comunica su resultado. |
| 5 | Pedido recibido | Consulta el mensaje de confirmación. | Reconoce que su pedido fue recibido correctamente. |

### ¿Qué ocurre si decide editar el pedido?

Si el estudiante selecciona la opción **«Editar pedido»**, el sistema debe permitir modificar los productos o cantidades seleccionadas.

Después de realizar los cambios, debe actualizarse el total y mostrarse nuevamente el resumen para que pueda verificarlo antes de confirmar.

### ¿Qué ocurre si confirma el pedido?

Cuando el estudiante selecciona **«Confirmar pedido»**, el sistema debe enviar la información del pedido y mostrar una señal visual clara cuando su recepción sea exitosa.

Por ejemplo:

**Pedido recibido correctamente.**

Tu pedido de 1 café americano y 1 sanduche, por un total de $4,25, ha sido registrado.

Si el sistema no logra confirmar la recepción, debe comunicarlo claramente y evitar presentar el pedido como recibido.

## 6. Criterios de aceptación del requisito

Se considerará que el requisito principal está correctamente representado en el diseño cuando:

- [ ] El estudiante pueda consultar los productos y sus precios.
- [ ] Pueda seleccionar los productos deseados.
- [ ] El sistema muestre un resumen del pedido con el total correcto.
- [ ] Exista una opción para editar el pedido antes de confirmarlo.
- [ ] El total se actualice cuando se modifiquen los productos o cantidades.
- [ ] Exista un control claramente identificado para confirmar el pedido.
- [ ] El sistema muestre una confirmación comprensible cuando el pedido sea recibido.
- [ ] El recorrido pueda completarse sin necesidad de explicar verbalmente el pedido.

## 7. Conclusión

El análisis del caso CaféU permite identificar que la principal necesidad del estudiante es realizar pedidos de manera rápida y comprensible durante sus descansos académicos, evitando depender de la comunicación verbal en una cafetería concurrida.

Por esta razón, el diseño debe priorizar la claridad del menú, la revisión de los productos seleccionados, la posibilidad de corregir errores y la confirmación del pedido. Estos elementos constituyen el punto de partida para desarrollar un prototipo centrado en las necesidades reales del usuario y en los principios de Interacción Humano-Computador.

---

**APE 4 — Fase 1 | CaféU — Requisito del Usuario**