Lumache
=====

.. _installation:

Instalando
------------

Para Usar o Lumache, Use o Pip:

.. code-block:: console

   (.venv) $ pip install lumache

Criando Receitas
----------------

Para Retornar Ingredientes Aleatórios,
Você Pode Utilizar ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

Esse ``Tipo`` De Parâmetro pode ser também: ``"Carne"``, ``"Peixe"``,
ou ``"vegetais"``. Todavia, :py:func:`lumache.get_random_ingredients`
Irá aumentar uma exception

.. autoexception:: lumache.InvalidKindError

Por Exemplo:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

