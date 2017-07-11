# Getting started

**Installing python**

The majority of the people in the McMorran group are currently using python 3, so new additions to the lab should just start with python 3. We used to subscribe to python 2.7 as recentl as 2016 for a number of reasons but mostly because many of the scientific tools and libraries had not yet been updated to python 3. This reason no longer holds true and we have therefore switched to python 3 as of 2017.
 
Our group generally uses the [anaconda](https://www.continuum.io/downloads) distribution of python.
To install just visit the page at the link and follow the directions.
It comes with many of the additional packages that are needed to do scientific programing and can help you get off the ground and started more quickly.
If you don’t like this batteries included approach feel free to download python and install individual packages as you need them.

**Learning python**

There are two major parts to learning how to use python for scientific projects.
First, learning the syntax (how to perform a loop, read/write files etc.) and second learning how to convert equations and scientific models into that syntax.
I found that the best way for me to learn the language (syntax) was to use it.
The best resource I have found to guide me through that process is Learn Python the Hard Way.
Working through all the exercises until you get to exercise 44, should cover the majority of the syntax and programing basics that you need to start working on a scientific project.
If you get bored of learning python the hard way you can look at code academy it is a little different format, but still a good way to learn python, syntax.
There are a number of good resources for learning how to use python for scientific programing instead of trying to list them here I have opted to incorporate links into the Jupyter notebooks in places that they are relevant.
This is meant to put things in context, but the reader should know that a huge part of being a successful programmer is having the ability to quickly find answers to a coding problem.
Often someone else has already asked the same question or part of the same question and all you need to do is find that information on google usually on a stack exchange post.

# Using python
Everyone in the group uses python differently but here is how I ([Jordan Chess](https://github.com/jordanchess)) do things.


*Rules/guidelines I try to follow*

1. Assume every line of code you write has an error.
    * Test things as often as you can. *This is where Jupyter notebooks come in handy.*
    * If you are confused about what your code is doing print or plot everything.
2. Just because your code ran doesn't mean your code is running correctly.
    * Always test your code on something you know the answer to.
3. Follow PEP8 guidelines
    * If your code is poorly formatted no one can read it not even your future self.
4. Comment, comment, comment.
    * I need to be better at this but if you don't comment your code it is much harder to read and understand which can cause big problems in the future if you have a bug or want to add functionality.
5. Don't optimize until after it is working.

*My general workflow*

1. Develop tools in a Jupyter notebook
2. Transfer those tools to a .py file
3. Upload that to github
4. Optimize that tool if needed generally just using python in the command line or sometimes in Spyder.
5. Use those tools on data or for simulations

# Tutorials
1. [Basic numpy functions and plotting](https://github.com/jordanchess/McMorran-group-tutorials/blob/master/Notebooks/Basic%20numpy%20functions%20and%20plotting.ipynb)
2. [A skills test](https://github.com/McMorranLab/McMorran-group-tutorials/blob/master/Notebooks/Skills%20test.ipynb)
3. [A cool site explaning the Fourier transform (DFT)](https://betterexplained.com/articles/an-interactive-guide-to-the-fourier-transform/)
4. [A more mathematical explanation](https://see.stanford.edu/materials/lsoftaee261/book-fall-07.pdf)
5. [Fourier transform Homework and Visualization notebook](https://github.com/McMorranLab/McMorran-group-tutorials/blob/master/Notebooks/FFT.ipynb)
