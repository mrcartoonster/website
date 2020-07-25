# Let's Get Started!

All right, before you head off and read my tutorials, I'm going to need you to
follow some *oppinionated guidelines*. There are some common Python tools I use
in Python development that are now ingrained in me and use everytime I write
Python code. They've become my *Best Practices* and I want to impart them to
you. Also, this'll help so when you start reading my tutorials, you're not
confused on what the modules do and why I always start with them. 

There are three Python modules that I use on the regular and each section after
this within will go into how to install them and the few commands you'll need
to know to get up and running with them.

# [Pyenv](./pyenv.md)

The first is `pyenv`. The `pyenv` module is a "Simple Python version
management" system. It nicely manages Python versions as well as setting
virtural environments. We'll be using the module to essentially set the Python
version we'll want to work with. `pyenv` gives us the ability to switch back
and forth Python versions without the need to actually installing them in our
machines. Want to use the latest Python version like 3.9.x or 4.0.xrcx? We it's
as simple as doing: `$ pyenv install 3.9.x`! You want to also want go back and
use Python 2.1.1? Again, `$pyenv install 2.1.1`. You now have both Python
versions 3.9.x and 2.1.1 and you'll be able to switch back and for locally and
globablly! You'll learn how in my [pyenv](./pyenv.md) section.

# [Poetry](./poetry.md)

You can manage virtual envrionments with `pyenv` alone. But, you're going to
want to do that with `poetry`. This package will give you the ability to not
only create virtual environments but also build out your packages and modules.
You'll thank me to introducing you to this power package when you create your
awesome Async Framework! This section I'll show you how to install properly as
well as the minimum commands to fly high with this package.
