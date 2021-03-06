# 馃柤 CSS Layout 

## 馃搻 Organizaci贸n
- `margin`
- `padding`
- `box-sizing`
- `position`
- `display`

### margin (top, right, bottom, left)
- Controla el espacio alrededor del elemento
    - `10px` (10px en todas las direcciones)
    - `10px 20px` (10px arriba y abajo; 20px en ambos lados)
    - `10px 20px 25px` (10px arriba, 20px en ambos lados, 25px abajo)
    - `10px 20px 25px 30px` (manecillas del reloj)

### padding (top, right, bottom, left)
- Controla el espacio dentro del elemento
    - `10px` (10px en todas las direcciones)
    - `10px 20px` (10px arriba y abajo; 20px en ambos lados)
    - `10px 20px 25px` (10px arriba, 20px en ambos lados, 25px abajo)
    - `10px 20px 25px 30px` (manecillas del reloj)

### box-sizing
- Calcular el tama帽o total de un elemento
    - `border-box` Toma en cuenta el padding y el borde de un elemento como parte de su tama帽o
    - `content-box` El padding y el borde suman al tama帽o del elemento

### position
- Espec铆fica la posici贸n de un elemento
    - `static` Valor por defecto
    - `relative` Posici贸n relativa al contenedor
    - `absolute` El elemento se posiciona en base al primer elemento en posici贸n *relativa*
    - `fixed` Posici贸n relativa a la pantalla del navegador
- Propiedades para modificar la posici贸n: `top | right | bottom | left` 

### display
- Espec铆fica el comportamiento de un elemento
    - `block` (Ocupa el 100% disponible de su contenedor) `header, section, h1, p, footer`
    - `inline` (Se comporta como texto)
    - `inline-block` (Apilar objetos horizontalmente)
    - `none` (Oculta el elemento)
    - `flex` (M贸dulo de CSS) 馃挌
    - `grid` (M贸dulo de CSS) 馃挌


#### Recursos

- 馃摴: [Web - CSS Layout (margin, padding, position, display)](https://youtu.be/1NNefYD91j8)
- [Layout - HTML](https://github.com/jujogi/dmi-web/blob/master/css/examples/layout.html)
- [Layout - CSS](https://github.com/jujogi/dmi-web/blob/master/css/examples/styles/layout.css)
