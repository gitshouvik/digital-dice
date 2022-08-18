# Simulating digital dice

This GitHub repository contains Monte Carlo simulations of the probability puzzles in the book **'_Digital Dice_'** **by Paul J. Nahin**. The author describes 21 problems based on "everyday real life." The solutions to these problems are implemented here in Python 3. 


![](https://pup-assets.imgix.net/onix/images/9780691158211.jpg)

The large part of the book is available on [Google Books](https://books.google.ch/books?id=bmhuaGP3FOEC&printsec=frontcover&hl=de&source=gbs_ge_summary_r&cad=0#v=onepage&q&f=false).

Much of the heavylifting in the codes provided here is performed by NumPy's random module. One of the notebooks uses Pandas to organize the outputs. The plots are done using Matplotlib. Finally, since some Monte Carlo simulations take numerous iterations to converge, we utilize a progress-bar to keep track of the loop index. This is done using [tqdm](https://github.com/tqdm/tqdm). Please ensure you have these packages before running the Jupyter notebooks here.

Installation instructions for tqdm can be found [here](https://github.com/tqdm/tqdm#installation). 
