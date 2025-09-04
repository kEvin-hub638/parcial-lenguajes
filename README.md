# Parcial 1 – Lenguajes de Programación

Este repositorio contiene la resolución del **Parcial 1** de la materia **Lenguajes de Programación**.  
Cada punto fue implementado en un lenguaje diferente, de acuerdo con el enunciado.

---

## Punto 1 – DFA en Python (abc)

Implementación de un autómata finito determinista que reconoce cadenas sobre el alfabeto `{a, b, c}`.

**Archivo:**  
- `abc_dfa.py`

**Ejecución:**
```bash
cd python
python3 abc_dfa.py
```

---

## Punto 2 – DFA en Python (abd, id)

Implementaciones de autómatas finitos deterministas adicionales.

**Archivos:**  
- `abd_dfa.py`  
- `id_dfa.py`

**Ejecución:**
```bash
cd python
python3 abd_dfa.py
python3 id_dfa.py
```

---

## Punto 3 – Calculadora de raíz cúbica en C (Flex + Bison)

Calculadora que obtiene la raíz cúbica de números reales usando **Flex** y **Bison** en **C**.

**Archivos:**  
- `calc.l`  
- `calc.y`  
- `Makefile`

**Ejecución:**
```bash
cd punto3
make run
```

---

## Punto 4 – Algoritmo de Euclides

Implementación del algoritmo recursivo de Euclides en dos lenguajes diferentes.

**Archivos:**  
- `euclides.c` (C)  
- `Euclides.hs` (Haskell)

**Ejecución en C:**
```bash
cd punto4/c
make run
```

**Ejecución en Haskell:**
```bash
cd punto4/haskell
make run
```

---

## Punto 5 – Serie de Maclaurin (ANTLR + Java)

Programa que calcula los **n términos** de la serie de Maclaurin para `e^x` usando **ANTLR** y **Java**.

**Archivos:**  
- `Maclaurin.g4`  
- `Eval.java`  
- `Main.java`  
- `Makefile`

**Ejecución:**
```bash
cd punto5
make run
echo "ex(x=2.5, n=8)" | make run
```
