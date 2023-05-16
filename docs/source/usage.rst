Usage
=====

.. _installation:

Run as Windows executable
------------

To use PySynthMRI as a Windows .exe file, follow the steps:

1. Download Release from: `PySynthMRI <https://github.com/FiRMLAB-Pisa/pySynthMRI/releases/download/v1.0.0/pySynthMRI-v1.0.0-windows-executable.zip>`_ 
2. unzip pySynthMRI-v1.0.0.zip
3. run PySynthMRI.exe


Run as Python
-------------
These instructions will give you a copy of the project up and running on your local machine,
using Linux or MacOS<br>
Make sure you have `Python <https://python.org/>` version >= 3.6.

To use PySynthMRI, first download and install dependencies:

Clone the repository:

.. code-block:: console

   (.venv) $ git clone https://github.com/FiRMLAB-Pisa/pySynthMRI.git


Create a [Python Virtual Environment](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)

Install required libraries:

.. code-block:: console
   pip install -r requirements.txt



.. Creating recipes
.. ----------------

.. To retrieve a list of random ingredients,
.. you can use the ``lumache.get_random_ingredients()`` function:

.. .. autofunction:: lumache.get_random_ingredients

.. The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
.. or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
.. will raise an exception.

.. .. autoexception:: lumache.InvalidKindError

.. For example:

.. >>> import lumache
.. >>> lumache.get_random_ingredients()
.. ['shells', 'gorgonzola', 'parsley']

