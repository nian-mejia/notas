- Una expresión algebraica es una combinación de constantes (números) y variables (elemento de un conjunto numérico representado por letras), unidos mediante las distintas operaciones matemáticas
- Generalmente las variables se representan con las últimas letras del alfabeto: 𝑢,𝑣,𝑤,𝑥,𝑦,𝑧. }
- $$3x^{2}+4x-5,\quad\dfrac{x+z}{y^{2}+x},\quad\dfrac{\sqrt{y}-4z}{z+y}$$
- ## Polinomios
-
- Un polimonio de la variable x es de la forma $$a_n+x^n+a_{n-1}x^{n-1}+\cdots+a_{1}x+a_{0}$$
- donde $a_n$ son número $$\mathbb R$$ llamado **Coheficientes** y n es un ==número entero positivo==
- el grado de un polinomio corresponde al mayor exponente de la variable que aparece en el polinomio.
- ## Suma y resta de polinomios
- Utilizamos las propiedades de la suma y el producto de números reales
- Ejemplo: $$(3x^2+7x-9 )+ (-5^3 x ^3- \frac{1}{5}x^2 + x-5) $$
- ![](https://media.githubusercontent.com/media/nian-mejia/notas/master/assets/image_1661638259802_0.png){:height 337, :width 787}
- ## Producto o multiplicación de polinomios
- Utilizamos las propiedades de la suma y el producto de números reales
- $$\begin{align*} 
  (3x - 4)(x^2+x) \\
  \text{\textcolor{Blue}{Se multiplica cada factor con el siguiente parentisis}} \\
  3x \cdot (x^2+x) +  (-4) \cdot (x^2+x) \\
  3x^3+3x^2 + (- 4x^2 + (-4x)) \\
  \text{\textcolor{Blue}{Se agrupan por grado}} \\
  3x^3+(3x^2-4x^2) - 4x \\
  3x^3 - x - 4x 
  \end{align*}
  $$
- ## División de polinimos
- Si 𝑃(𝑥) y 𝐷(𝑥) son polinomios tales que el grado de 𝑃(𝑥) es mayor o igual que el grado de 𝐷(𝑥) y si 𝐷(𝑥)≠0,
	- $$\frac{P(x)}{D(x)} = Q(x) + \frac{R(x)}{D(x)} $$
	  $$D(x) \cdot \frac{P(x)}{D(x)} = Q(x) + \frac{R(x)}{D(x)}  \cdot D(x) $$
	  $$𝑃(𝑥)=𝐷(𝑥)⋅𝑄(𝑥)+𝑅(𝑥)$$
- Dividir 5𝑥3−2𝑥+1 entre 𝑥+1
- ### Pasos:
	- 1 ) Se ordenan ambos polinomios en forma descendente con respecto a las potencias de 𝑥x, y si falta alguna potencia se agrega con coeficiente 0. En este caso, sólo falta agregar 0x^2 al dividendo.
	- Para obtener el primer término del cociente, se divide el primer término del dividendo entre el primer término del divisor. En este caso, $\frac{5𝑥^3}{x}=5x^2$ (éste será el primer término del cociente)
	- Se multiplica el divisor por el primer término del cociente: $$(x+1)\cdot 5x^2 = 5x^3+5x^2$$ y este resultado se resta del dividendo
	- El proceso termina cuando el polinomio que se obtiene en el último renglón es de menor grado que el divisor. En este caso, como el divisor es un polinomio de grado 11 y el polinomio del último renglón es de grado 0
	  id:: 630c1b52-c42d-4b5d-9d4f-277dacb08514
	- {{{image-l image_1661738156984_0.png}}}
- ## División sintética
- La división sintética es un método rápido para dividir polinomios cuando el divisor es de la forma x−c, con c un número real $(𝑐∈ℝ)$
- Dividir $$x^4 - 3^2 + 2x - 5 $$ entre $x + 2$
- ### Pasos:
	- Sólo se escriben los coeficientes del dividendo y el valor de $-𝑐$ (en este caso -𝑐=−2). Si falta alguna potencia de 𝑥 se escribe 0 como coeficiente.
	- Se traza una lı́nea horizontal debajo del los coeficientes del polinomio, dejando un espacio. Se escribe el primer coeficiente 1, debajo de la lı́nea, se multiplica por 𝑐 (1×−2=−2) y el resultado se escribe en el espacio intermedio, debajo del segundo coeficiente y se suman estos dos números (0+(−2)=−2). El resultado se multiplica por 𝑐 y se suma al tercer coeficiente. Se repite este proceso hasta terminar los coeficientes del dividendo
	- El residuo es el último número del último renglón (𝑅(𝑥)=−5) y el cociente 𝑄(𝑥) es el polinomio de un grado menor que el dividendo y cuyos coeficientes son los números del último renglón, excepto el último. En este caso, $$Q\left(x\right) =x^{3}-2x^{2}+x+0$$
	- {{{image-l image_1661739226825_0.png}}}