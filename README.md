# css-flex-bash3

# CSS Flexbox - Resumen

## Contenedor y Elementos Flex

```css
.contenedor {
    display: flex;
}

.elemento {
    width: 25%;
    background-color: aqua;
}

Dirección y Envoltura
.contenedor {
    display: flex;
    flex-direction: row-reverse;
}

.contenedor {
    display: flex;
    flex-direction: column;
}

.contenedor {
    display: flex;
    flex-direction: column-reverse;
}

.contenedor {
    display: flex;
    flex-wrap: wrap;
}

.contenedor {
    display: flex;
    flex-wrap: wrap-reverse;
}

.contenedor {
    display: flex;
    flex-direction: row-reverse;
    flex-wrap: wrap-reverse;
}

.contenedor {
    display: flex;
    flex-flow: row-reverse wrap-reverse;
}


Alineación y Justificación

.contenedor {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: flex-start;
}

.contenedor {
    display: flex;
    flex-direction: row-reverse;
    flex-wrap: wrap;
    justify-content: flex-end;
}

.contenedor {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
}

.contenedor {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-between;
}

.contenedor {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-around;
}

Alineación de Elementos
.contenedor {
    height: 240px;
    display: flex;
    flex-flow: row wrap;
    justify-content: flex-start;
    align-items: stretch;
}

.contenedor {
    height: 240px;
    display: flex;
    flex-flow: row wrap;
    align-items: flex-start;
}

.contenedor {
    height: 240px;
    display: flex;
    flex-flow: row wrap;
    align-items: flex-end;
}

.contenedor {
    height: 240px;
    display: flex;
    flex-flow: row wrap;
    align-items: center;
}

.contenedor {
    height: 240px;
    display: flex;
    flex-flow: row wrap;
    align-items: baseline;
}

Alineación de Filas

.contenedor {
    height: 240px;
    display: flex;
    flex-flow: row wrap;
    align-content: stretch;
}

.contenedor {
    height: 240px;
    display: flex;
    flex-flow: row wrap;
    align-content: flex-start;
}

.contenedor {
    height: 240px;
    display: flex;
    flex-flow: row wrap;
    align-content: flex-end;
}

.contenedor {
    height: 240px;
    display: flex;
    flex-flow: row wrap;
    align-content: center;
}

.contenedor {
    height: 240px;
    display: flex;
    flex-flow: row wrap;
    align-content: space-between;
}

.contenedor {
    height: 240px;
    display: flex;
    flex-flow: row wrap;
    align-content: space-around;
}

Propiedades Interesantes de Flexbox
Order

.contenedor {
    display: flex;
}

.elemento:nth-child(even) {
    order: 1;
}

Flex

.contenedor {
    display: flex;
}

.elemento {
    flex: 1 1 0;
}

.elemento:nth-child(4) {
    flex-grow: 3;
}


