# 馃梻 Pseudo Classes
Especifica un estado especial del elemento seleccionado.


```
selector:pseudoClase { propiedad: valor; }
```

- Pseudo Clases: `:hover :focus :active :first-child :last-child :nth-child :checked :visited`
    - `hover`: Cuando el usuario se posiciona sobre el elemento
    - `focus`: Cuando el usuario hace clic en un input de un formulario
    - `active`: Cuando el usuario hace click en un enlace o bot贸n
    - `first-child`: Selecciona el primer elemento de un grupo
    - `last-child`: Selecciona el 煤ltimo elemento de un grupo
    - `:nth-child`: Selecciona uno o m谩s elementos seg煤n una condici贸n:
        - `:nth-child(odd)`: Selecciona los elementos en posici贸n impar
        - `:nth-child(even)`: Selecciona los elementos en posici贸n par
        - `:nth-child(5n)`: Selecciona los elementos 5, 10, 15, etc...
        - `:nth-child(3n+4)`: Selecciona los elementos 4, 7, 10, 13, etc...
    - `:checked`: Cuando el usuario elige alguna opci贸n del form (checkbox - option)
    - `:visited`: Cuando el usuario ha visitado un enlace

 ---

# 馃摌 Pseudo Elements

No describen un estado especial sino que, permiten a帽adir estilos a una parte concreta del documento.

```
selector::pseudoElemento { propiedad: valor; }
```

- Pseudo Elementos: `::before ::after`

---

#### Recursos
- 馃摴: [Web - CSS Media queries](https://youtu.be/ylvao_zCbAk)

