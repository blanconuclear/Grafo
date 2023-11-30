# Normas Grafo Relacional

## 1:N

- La clave del 1 para para la N.
- Si es (0,1), la clave será foránea y alternativa.

  ![Ejemplo](/img/13%201N.png)

# 1:1

- Todas las 1:1 son CADIDATAS (N).

- La clave del (1,1) pasa para el (0,1) como foránea

  ![Ejemplo](/img/11%20con%2001.png)

- Si es (0,1) en los 2 lados. Se crea una tabla nueva. Una clave será principal y foránea, la otra solo foránea.

  ![Ejemplo](/img/11%20con%2001%20ambos%20lados.png)

## N:M

- Si en la núeva tabla ya hay una clave principal, solo una de las otras va a ser principal y foránea, la otra solo es foránea. Si no, son las dos principales y foráneas.

  ![Ejemplo](/img/NM%20con%20clave%20principal.png)

### (en reflexiva)

- Solo se ponen las 2 claves de la reflexiva.
- Las 2 son foráneas y principales.
- Las 2 se enlazan con la otra tabla.
