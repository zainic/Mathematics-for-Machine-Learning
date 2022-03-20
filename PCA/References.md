## Books
We tend to write our courses from scratch based on what we think is important to include and introduce things in the order we think presents the material in the most elegant and illuminating way - we don't just go through a particular set textbook. So there isn't an exact 'model text' that we are following in this course. But, our way of thinking about things is informed by the textbooks we use, the teachers who taught us, how we use things in research and by interactions with our own students - so of course all sorts of textbooks are useful.

+ Deisenroth et al.: Mathematics for Machine Learning, Cambridge University Press, 2018

+ Bishop: Pattern Recognition and Machine Learning, MIT Press, 2006, Chapter 12.1

## Links

If you would like to work offline on the Jupyter notebooks, you can download all the notebooks for this course from

https://drive.google.com/open?id=1yjYM3OV979ETuHO9tUUxjUW4cHJOcuNV

To learn how to setup an offline environment, we have provided a document for setting Jupyter notebooks with Anaconda.

https://docs.google.com/document/d/1Sa5zuRWrcQpPftfrTPxD3EyzQ3J7QCBc031ivTxD4uI/edit?usp=sharing

Ortogonal Complement

https://en.wikipedia.org/wiki/Orthogonal_complement

http://mathworld.wolfram.com/OrthogonalDecomposition.html

## Probably Important Equation

![equation](https://latex.codecogs.com/svg.image?\tilde{x_n}&space;=&space;\sum_{j=1}^{M}&space;\beta_{jn}&space;b_j)

![equation](https://latex.codecogs.com/svg.image?J&space;=&space;\frac{1}{N}\sum_{n=1}^{N}&space;\left\|&space;x_n&space;-&space;\tilde{x_n}\right\|^2)

![equation](https://latex.codecogs.com/svg.image?\frac{\partial&space;J}{\partial&space;\tilde{x_n}}&space;=&space;-\frac{2}{N}\left(x_n&space;-&space;\tilde{x_n}\right)^T)

![equation](https://latex.codecogs.com/svg.image?\beta_{jn}&space;=&space;x_n^T&space;b_j,&space;\;&space;j=1,...,M)

![equation](https://latex.codecogs.com/svg.image?x_n&space;-&space;\tilde{x_n}&space;=&space;\sum_{j=M-1}^{D}\left(b_j^T&space;x_n\right)b_j)
![equation](https://latex.codecogs.com/svg.image?J&space;=&space;\sum_{j=M&plus;1}^{D}&space;b_j^T&space;S&space;b_j)
