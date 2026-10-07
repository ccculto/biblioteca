## Ejercicio 1

Comando:
```bash
git log --oneline
```

Resultado:
```
6d72679 (HEAD -> master) Añade anotaciones de la biblioteca
1a384d3 Ignora archivos temporales
e30f6c0 Descripción del proyecto
```

## Ejercicio 2 — Trabajo con ramas

Comando ejecutado:
```bash
git log --oneline --graph --all
```

Resultado:
```text
*   255efeb Fusiona la gesti├│n de usuarios
|\  
| * 7bab258 Completado los datos de usuario
| * 367aeeb Crea la ficha de usuario
* |   6ac0957 Fusiona la gesti├│n de libros
|\ \  
| |/  
|/|   
| * 3a1bad7 Completa los datos del libro
| * 8537c3d Creada ficha de libro
|/  
* 228b76c A├▒ade la soluci├│n del ejercicio 1
* 6d72679 A├▒ade anotaciones de la biblioteca
* 1a384d3 Ignora archivos temporales
* e30f6c0 Descripci├│n del proyecto
```