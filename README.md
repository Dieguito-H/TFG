# Teorema de Takens como herramienta de reconstrucción del espacio de fases de sistemas estocásticos fuera del equilibrio
**Autor**: Diego Hermana García-Agulló  
**Tutor**: Lucia Benito Barca  
**Universidad**: Francisco de Vitoria  
**Grado**: Ingeniería Matemática con título propio en Quantum Computing

---

## Códigos para el desarrollo del proyecto en MATLAB
- [`Sistemas_deterministas.mlx`](Sistemas_deterministas.mlx)
  En este codigo se incluye el desarrollo previo para entender la dinámica de los sistemas amortiguados en disintos escenarios a traves de la ecuación de Langevin.

-Simulación de la segunda Ley de Newton.  
-Sistema subamortiguado.

-Sistema sobreamortiguado.

-Sistema sobreamortiguado+fuerza forzante.

Todos estas simulaciones se plantean para cuatro escenarios distintos.

-F=0.

-F=costante.

-F=-kx (Ley de Hook).

-F=acoplamiento por la ecuación de Langevin.


- [`Langevin.mlx`](Langevin.mlx)
  
  Simulación de la ecuación de Langevin incluyendo la parte estocástica. En el codigo se incluyen:
  
  -Variación de la componente de rigidez.
  
  -Variación de la componente de viscosidad.
  
  -Variación de la Temperatura.
  
  -Desarrollo de la Ecuación de Langevin.

- [`mallado.mlx`](mallado.mlx)

  En este código se desarrolla un mallado en las trayectorias de las observables para posteriormente contar las trayectorias de cada una de las celdas y obtener un vector resultante, creando el espacio de fases para observar la dinámica de la simulación.

- [`TTakensEq.mlx`](TTakensEq.mlx)

  En el archivo se muestra un primer desarrollo del Teorema de Takens en sistemas deterministas.

- [`TTakensNo.mlx`](TTakensNo.mlx)

  En este código se plantea el Teorema de Takens a sistemas estocásticos fuera del equilibrio termodinámico

- [`suma_de_rotaciones_real.mlx`](suma_de_rotaciones_real.mlx)

  En el archivo suma de rotaciones real se haya el código utilizado para calcular el rotacional de cada una de las simulaciones en las que no se utiliza el Teorema de Takens, para ello, se calcula una media de los rotacionales de 10 simulaciones distintas.
  
- [`Suma_rotaciones_reconstruido.mlx`](Suma_rotaciones_reconstruido.mlx)

  En el archivo suma de rotaciones reconstruido se haya el código utilizado para calcular el rotacional de cada una de las simulaciones en las que se utiliza el Teorema de Takens, para ello, se calcula una media de los rotacionales de 10 simulaciones distintas.

- [`mediacomparada.mlx`](mediacomparada.mlx)
  
  En este fichero se muestra la evolución de la media del rotacional a lo largo del tiempo de 5 simulaciones para distintos valores de rigidez.

- [`mediaVcomparada.mlx`](mediaVcomparada.mlx)

  En este fichero se muestra la evolución de la media del rotacional a lo largo del tiempo de 5 simulaciones para distintos valores de viscosidad.
  
- [`informacionmutua.mlx`](informacionmutua.mlx)

  En este código se muestra la selección del retardo temporal para distintos valores de rigidez y de viscosidad.


