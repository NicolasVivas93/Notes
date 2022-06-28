## Introducción a Flexbox
Flexbox es una forma de disponer items en filas y columnas. Estos items se harán flexibles (es decir, se van a achicar o agrandar) de acuerdo a ciertas reglas que definas.

Flexbox vendría a ser un conjunto de propiedades que te permiten poner las cosas donde vos las necesites. Algunas propiedades se aplican a los **flex containers** mientras que otras se aplican a los **flex items**.

Los ***flex containers*** serían cualquier elemento que contenga la propiedad `display: flex;`.
Un ***flex item*** sería cualquier elemento que viva *directamente* dentro del flex container. Generalmente tiene la propiedad `flex: 1;`

Ahora un flex item tambien puede constituirse en flex container y tener hijos que se conviertan en flex items.

La propiedad `flex` es un shorthand (método abreviado) de las propiedades: `flex-grow` , `flex-shrink` y `flex-basis`.

![Flex-Shorthand](../images/flex-shorthand.png)


