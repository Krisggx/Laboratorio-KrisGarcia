# Interpolación polinomial de Newton

Página web que resuelve el método de interpolación polinomial de Newton (diferencias divididas) para cualquier conjunto de puntos.

## Qué hace

1. Recibe n puntos (xᵢ, f(xᵢ)).
2. Construye la tabla de diferencias divididas.
3. Muestra los coeficientes b₀, b₁, …, bₙ.
4. Escribe el polinomio en forma de Newton:
   `P(x) = b0 + b1(x − x0) + b2(x − x0)(x − x1) + ...`
5. Muestra el polinomio desarrollado (forma estándar).
6. Verifica el polinomio en los puntos dados y permite evaluarlo en cualquier x.

## Cómo usarlo

Abra `index.html` en cualquier navegador. No necesita instalar nada ni conexión a internet.

Para verlo en línea con GitHub Pages: en el repositorio vaya a **Settings → Pages**, elija la rama `main` y la carpeta `/ (root)`, y guarde. La página quedará en `https://<usuario>.github.io/<repositorio>/`.

## Ejemplo

Con los puntos (1, 1), (2, 8), (3, 27), (4, 64):

- Polinomio de Newton: `P(x) = 1 + 7(x − 1) + 6(x − 1)(x − 2) + 1(x − 1)(x − 2)(x − 3)`
- Polinomio desarrollado: `P(x) = x³`
- P(5) = 125
