# Simulating digital dice


Can two wrongs be right? The plot below is a demonstration of how two stochastic processes have negative drifts separately but a random combination of those two leads to drift which is positive! This is known as [Parrondo's paradox](https://en.wikipedia.org/wiki/Parrondo%27s_paradox).

![image](https://user-images.githubusercontent.com/30939351/185399330-39b959cb-53a4-4b7b-afd7-cdd02ef75cbe.png)


This GitHub repository contains a Monte Carlo simulation resulting in above plot and all the other interesting probability puzzles in the book **'_Digital Dice_'** **by Paul J. Nahin**. The author describes 21 problems based on "everyday real life." The solutions to these problems are implemented here in Python 3. 

The large part of the book is available on [Google Books](https://books.google.ch/books?id=bmhuaGP3FOEC&printsec=frontcover&hl=de&source=gbs_ge_summary_r&cad=0#v=onepage&q&f=false).

Much of the heavylifting in the codes provided here is performed by NumPy's random module. One of the notebooks uses Pandas to organize the outputs. The plots are done using Matplotlib. Finally, since some Monte Carlo simulations take numerous iterations to converge, we utilize a progress-bar to keep track of the loop index. This is done using [tqdm](https://github.com/tqdm/tqdm). Please ensure you have these packages before running the Jupyter notebooks here.

Installation instructions for tqdm can be found [here](https://github.com/tqdm/tqdm#installation). 



![](https://pup-assets.imgix.net/onix/images/9780691158211.jpg)

