okexcept with no_traceback
==========================

.. toctree::

This shows traceback and exception (default ``:okexcept:`` behavior):

.. ipython:: python
	:okexcept:

        # :okexcept: option without argument
        1 / 0

This only shows the exception without traceback (``:okexcept:`` with ``no_traceback`` argument):

.. ipython:: python
	:okexcept: no_traceback

        # :okexcept: option with no_traceback argument
        1 / 0


The same with decorators:

.. ipython:: python

	@okexcept
        # @okexcept pseudodecorator without argument
        1 / 0

        @okexcept no_traceback  # noqa: E999
        # @okexcept pseudodecorator with no_traceback argument
	1 / 0
