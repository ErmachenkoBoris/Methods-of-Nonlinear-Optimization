# Экзаменационный билет №7
## 1.Связь знакоопределенности симметрической матрицы со знаками собственных чисел.

Пусть A - симметрическая матрица. A называется неотрицательно определенной (A>=0), если для любого d
![](https://latex.codecogs.com/svg.latex?d^{T}Ad\geq&space;0), где d - вектор

Положительно определена ![](https://latex.codecogs.com/svg.latex?d^{T}Ad>&space;0)

Знаконеопределена, если существует вектор d', что 

![](https://latex.codecogs.com/svg.latex?(d')^{T}Ad'>&space;0) и ![](https://latex.codecogs.com/svg.latex?(d'')^{T}Ad''<&space;0)

Положительная определенность матрицы связана с положительностью ее главных миноров

Матрица положительно определена, если ![](https://latex.codecogs.com/svg.latex?\Delta_{1}>0,\Delta_{2}>0,...,\Delta_{n}>0)

![](https://github.com/nifadyev/Methods-of-Nonlinear-Optimization/blob/master/images/ticket07-1.png?raw=true)

Матрица отрицательно определена, если знаки главных миноров чередуются.
![](https://latex.codecogs.com/svg.latex?\Delta_{1}<0,\Delta_{2}>0,\Delta_{3}<0,\Delta_{4}>0)
Если хотя бы 1 минор обратился в 0, то критерий не применим(Критерий Сильвестра)

Напомним, что характер знакоопределенности симметрической матрицы ![](https://latex.codecogs.com/svg.latex?A&space;=&space;A^{T}) определяется по знаку квадратичной формы ![](https://latex.codecogs.com/svg.latex?d^{T}Ad) для d ≠ 0. Если знак может быть различен для разных d , то матрицу A называют знаконеопределенной.

Известно, что собственные числа ![](https://latex.codecogs.com/svg.latex?\lambda_{1},\lambda_{2},...,\lambda_{n}) симметрической матрицы всегда действительны, а представление соответствующей ей квадратичной формы в каноническом виде приводит к выражению ![](https://latex.codecogs.com/svg.latex?\sum_{i=1}^{n}\lambda_{i}*u_{i}^{2}). Таким образом, знаки набора собственных чисел ![](https://latex.codecogs.com/svg.latex?\lambda_{1},\lambda_{2},...,\lambda_{n}) полностью определяют характер знакоопределенности матрицы, например при ![](https://latex.codecogs.com/svg.latex?\lambda_{i}\geq0(i=1,...,n)) матрица A будет неотрицательно определена.
