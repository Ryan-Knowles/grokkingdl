# Notes / Practice Code for the [Grokking Deep Learning book by Andrew Trask](https://www.manning.com/books/grokking-deep-learning)
----


## Installing on MacOS
----

```bash
# For python 3.11.5, you can update this as needed using pyenv
mkvirtualenv -p ~/.pyenv/versions/3.11.5/bin/python <pkg-name>-py3.11.5
workon <pkg-name>-py3.11.5
pip install -r requirements

# Add virtualenv to ipython as a kernel
ipython kernel install --user --name <pkg-name>-py3.11.5

# Bootup juypter lab
jupyter-lab
```