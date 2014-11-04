GADSDC Hacker Night: NLTK and Joblib
===



Get Ready!!
---

*Libraries you'll need*:

- [joblib](https://pythonhosted.org/joblib/parallel.html) (pip install)
- [**NLTK**](http://www.nltk.org/)
- [**pandas**](http://pandas.pydata.org/)
- [pp](http://www.parallelpython.com/) (from source)
- [**numpy**](http://www.numpy.org/)
- [*time*](https://docs.python.org/2/library/time.html)
- [*pickle*](https://docs.python.org/2/library/pickle.html)

**Bold** are included in the most recent Anaconda distro.
*Italic* comes standard.

NLTK
---

[Go here to read in its entirety “Natural Language Processing with Python”](http://www.nltk.org/book/) by Steven Bird, Ewan Klein, and Edward Loper, the developers of the NLTK module. They kindly have included exercises in their books throughout the documentation and at the end of each chapter. Check out Chapter 1 if you’ve never done any NLTK before and complete all the exercises at the end!

Parallel Computing
---

1. “Pickle” a `list`, a `pandas.DataFrame`, a `numpy.array`, a linear regression model, any python object really to file and then read it back in using `joblib.dump()` and `joblib.load()`. Compare the pickled files and the process of the pickling methods with the modules [pickle](https://docs.python.org/2/library/pickle.html), [joblib](https://pythonhosted.org/joblib/parallel.html), and [numpy](http://docs.scipy.org/doc/).


2. Write a function that will take an integer and print its square.  Make a randomized data set of 1,000, 10,000, and 100,000 data points and time it the execution of your function on all the data points with `time` or any other similar module. Now parallelize the computation using the `joblib.Parallel` class.  Open your activity monitor or task manager while you do each of these and filter for python tasks.

3. You can also try out [parallel python](http://www.parallelpython.com/), or `pp` to parallelize tasks.
