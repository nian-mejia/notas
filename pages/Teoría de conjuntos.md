- Un conjunto es una colección de objetos, llamados **elementos del conjunto**, se puede describir como:
	- **Por extensión**: Haciendo una lista explicita de los elementos, separados por coma y encerrados entre llaves.
		- $$A=\{{a,e,i,o,u}\}$$
	- **Por comprensión:** Dando una serie de condiciones que deben cumplir los conjuntos
		- $$A=\{ {x/x \text{ es una vocal de la palabra eucalipto}} \}$$
- Si un conjunto no tiene elementos se llama conjunto vacío y se denota así \emptyset ó  \{ \}
- #### Conjuntos finitos e infinitos
	- Si un conjunto es vacío o su número de elementos es un número natural , se dice que el conjunto es **finito**. O si no se puede saber el numero de elementos que tiene un conjunto, se dice que es  **infinito**
	- Sea $$ A= \{{ \frac{1}{2},\frac{1}{3},14,15,…} \} $$  A es infinito ya que no podemos asignar un número natural para su número de elementos.
- #### Pertenece y no pertenece
	- Si A es un conjunto, decimos que a **pertenece** a  **A** y escribimos a ∈ A, si a es un elemento de A. En caso contrario decimos que a **no pertenece a** A y escribimos a ∉ A. En el último ejemplo
	- $$\frac{1}{2} \in A \text{ y }  5 \notin A $$
- ### Subconjuntos
	- Si A y B son conjuntos, decimos que A **es subconjunto de** B y escribimos A ⊆ B, si todo elemento de A es también elemento de B. En caso de que haya **al menos un elemento** en el conjunto A que no pertenece al conjunto B, decimos que A **no es subconjunto de** B, y escribimos A⊈B. Usando **diagramas de Venn**, podemos representar gráficamente los conjuntos. Por ejemplo:
	- ![](https://media.githubusercontent.com/media/nian-mejia/notas/master/assets/image_1660575441799_0.png)
	- Ejemplos:
	- Sean $$A=\{{ a,e,i,o,u }\}$$ y B=$$ \{ {x/x \text{es una letra del abecedario}}\}$$. Entonces A⊆B, pero  B⊈A
	  id:: 62fa5f55-1ff2-4954-b1dd-02831a0473ee
- ### Operaciones entre conjuntos
	- **Unión:**
		- Sean A y B dos conjuntos. Definimos la unión de $A \cup B$, como el conjunto
		- $$A∪B=\{ {x/x∈A ó x∈B}\} $$
		- ![image.png](../assets/image_1660577575063_0.png){:height 386, :width 645}
	- **Intersección:**
		- Sean A y B dos conjuntos. Definimos la intersección de A y B, denotada A∩B, como el conjunto  $A∩B={x/x∈ A \text{ y } x∈B}$
		- ![](https://media.githubusercontent.com/media/nian-mejia/notas/master/assets/image_1660577910805_0.png)
	- Ejemplos unión e intersección
	- ![](https://media.githubusercontent.com/media/nian-mejia/notas/master/assets/image_1660578814603_0.png){:height 386, :width 469}
	- **Complemento:**
		- Si U es un conjunto universal y A es un subconjunto de U, definimos el complemento de A, denotado A', como el conjunto $A'=\{{x|x ∈ U \text{ y } x∉A}\}.$
		- ![](https://media.githubusercontent.com/media/nian-mejia/notas/master/assets/image_1660579712001_0.png){:height 338, :width 444}
			- **Ejercicios ley de morgan**
			- ![](https://media.githubusercontent.com/media/nian-mejia/notas/master/assets/image_1660580296576_0.png){:height 472, :width 559}
	- **Diferencia:**
		- Sean A y B dos conjuntos. Definimos la diferencia de A y B, denotada A−B, como $A−B=\{{x/x∈A \text{ y } x∉B}\}$
		- ![image.png](../assets/image_1660585871842_0.png)
	- **Diferencia simétrica:**
		- En teoría de conjuntos, la diferencia simétrica de dos conjuntos es una operación cuyo resultado es otro conjunto que contiene a aquellos elementos que pertenecen a uno de los conjuntos iniciales, pero no a ambos a la vez.
		- Sean A y B dos conjuntos. Definimos la diferencia simétrica de A y B, denotada AΔB, como $$AΔB=(A∪B)−(A∩B)$$, o equivalentemente $$AΔB=(A−B)∪(B−A)$$.
		- ![](https://media.githubusercontent.com/media/nian-mejia/notas/master/assets/image_1660586293455_0.png){:height 403, :width 728}
- **Resumen de conjuntos** ![Tema01.pdf](../assets/Tema01_1660590011568_0.pdf)
- **Taller de conjuntos** ![[02.2020 - MBas] Taller 01.pdf](../assets/[02.2020_-_MBas]_Taller_01_1660590139195_0.pdf)