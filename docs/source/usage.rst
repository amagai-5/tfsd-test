Usage
=====

.. _installation:

Installation
------------

Project setup

.. code-block:: console

   npm install 

Compiles and hot-reloads for development
----------------

.. code-block:: console
   
   npm run serve

Compiles and minifies for production
----------------

.. code-block:: console
   
   npm run build


Run your tests
----------------

.. code-block:: console
   
   npm run test

Lints and fixes files
----------------

.. code-block:: console
   
   npm run lint





To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

