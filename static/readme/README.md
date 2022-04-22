# Tareas

## Tarea 1
## Experimentar con
* @import
* var()
* calc()

### Resultado de `@import`
```css
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300&display=swap');
```

### Resultado de `var()`
```css
:root {
    /*COLORS*/
    --light-color: #f7f7f7;
    /*UTILS*/
    --space-unit: 8px;
    --font-fam: 'Montserrat', sans-serif;
}
```
```css
body {
    background-color: var(-light-color);
    font-family: var(--font-fam);
}
```

### Resultado de `calc()`
```css
.container {
    max-width: 900px;
    margin: calc(var(--space-unit) * 5) auto 0;
}
```