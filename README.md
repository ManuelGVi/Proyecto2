# Compilador 

- Despues de clonar se deberá hacer lo siguiente

1. npm install
2. npm install antlr4

Deberás asegurarte de que tu computadora tenga instalada la versión de ANTLR4 previamente.

-- Para compilar el archivo g4 utiliza el script

```
antlr -Dlanguage=JavaScript -o src/ ./grammar/Dixo.g4
```

