# Find all preperiodic points of Dynamics System over function fields
<img src="images/logo_sagemath+icon_oldstyle.png" width=200> 
The goal of the project is to find pre-periodic points of a [dynamical system](https://en.wikipedia.org/wiki/Dynamical_system) defined over function fields by implementing the Hutz algorithm in the open-source environment "Sage" based on the Python language, using algebraic and arithmetic properties of the function field to calculate the pre-periodic points more efficiently and fast. </br> 
By using the algorithm we want to get a list of graphs of periodic points similar to the Poonen hypothesis.
</br>

**HUTZ algorithm** : https://arxiv.org/pdf/1210.6246.pdf ,
**Poonen hypothesis** : https://arxiv.org/pdf/math/9512217.pdf

</br>

In the **test** folder there's Jupyter Notebook file which has some python code to test the functions we added to Sage ,we put the functions we wrote at the start of the file and after that we runed this functions on some dynamic systems we chose to show the graphs of the pre-periodic points.  


In the **images** folder there's some pictures of the graphs we got after runnig the algorithm on a number of **Dynamic Systems** defined over **Function Fields** over 
**Finite Field** .

</br>

**Graph of pre-periodic points :** 
</br>

![](images/pre-periodic-graph.png)

</br>

<img src="https://latex.codecogs.com/svg.image?f^{j}(p),f^{j&plus;1}(p),...,f^{j&plus;k-1}(p)" title="f^{j}(p),f^{j+1}(p),...,f^{j+k-1}(p)" />&nbsp;&nbsp;&nbsp;are periodic points (also pre-periodic). <br/>
<img src="https://latex.codecogs.com/svg.image?p,f(p),f^{2}(p),..." title="p,f(p),f^{2}(p),..." />&nbsp;&nbsp;&nbsp;are only pre-periodic points because after a number of iterations they become periodic (as shown in the picture above)
