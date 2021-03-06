# 馃 Condicionales
En cualquier lenguaje de programaci贸n y en la vida en general, necesitamos tomar decisiones y realizar acciones basadas de un input.
- Si en mi cuenta bancaria no tengo dinero, no puedo comprar nada.
- Si las vidas de mi personaje llegan a cero, el juego se termina.
- Si no estoy registrado, no puedo a帽adir fotograf铆as.

---

## Declaraciones (if & else)

Los condicionales utilizan los [operadores de comparaci贸n](https://github.com/jujogi/dmi-web/blob/master/javascript/docs/03-variables.md):
- `===`
- `!==`
- `&&`: (Y) - Definir 2 o m谩s condiciones y se deben cumplir
- `||`: (O) - Si una de las 2 o m谩s condiciones se cumplen

Condicional simple
```
if (condici贸n) {
  c贸digo a ejecutar si la condici贸n es verdadera
} else {
  ejecuta este otro c贸digo si la condici贸n no se cumple
}
```


## Declaraci贸n (else if)
Lo utilizamos cuando necesitamos realizar m谩s de 2 validaciones.
```
if (comida === 'carne') {
  console.log('Al usuario le gusta la carne');
} else if(condici贸n === 'pollo') {
  console.log('Al usuario le gusta el pollo');
} else if(condici贸n === 'pescado'){
    console.log('Al usuario le gusta el pescado');
} else {
    console.log('El usuario no tiene ninguna preferencia');
}
```

## Ejemplo cotidiano
Aplicaci贸n que verifica si el usuario ha verificado su cuenta mediante el correo electr贸nico
```
if (user.isActive === false) {
    console.log('Primero debes activar tu cuenta');
} else {
    console.log('Puedes iniciar sesi贸n en la aplicaci贸n');
}
```

#### Recursos

- 馃摴: [Web - Conditionals & Functions](https://youtu.be/jnCAAMKoO6g)
- [Condicionales](https://github.com/jujogi/dmi-web/blob/master/javascript/examples/js/conditionals.js)
