Coding quality
###############

I value software quality. Higher quality software has fewer defects, better security, and better performance, which leads to happier users who can work more effectively.
Code reviews are an effective method for improving software quality. McConnell (2004) suggests that unit testing finds approximately 25% of defects, function testing 35%, integration testing 45%, and code review 55-60%. 
While this means that none of these methods are good enough on their own and that they should be combined, clearly code review is an essential tool here.

This library is therefore developed with several techniques, such as coding styling, low complexity, docstrings, reviews, and unit tests.
Such conventions are helpfull to improve the quality, make the code cleaner and more understandable but alos to trace future bugs, and spot syntax errors.


library
**************

The file structure of the generated package looks like:


.. code-block:: bash

    path/to/ismember/
    ├── .editorconfig
    ├── .gitignore
    ├── .pre-commit-config.yml
    ├── .prospector.yml
    ├── CHANGELOG.rst
    ├── docs
    │   ├── conf.py
    │   ├── index.rst
    │   └── ...
    ├── LICENSE
    ├── MANIFEST.in
    ├── NOTICE
    ├── ismember
    │   ├── __init__.py
    │   ├── __version__.py
    │   └── ismember.py
    ├── README.md
    ├── requirements.txt
    ├── setup.cfg
    ├── setup.py
    └── tests
        ├── __init__.py
        └── test_ismember.py


Style
********

This library is compliant with the PEP-8 standards.
PEP stands for Python Enhancement Proposal and sets a baseline for the readability of Python code.
Each public function contains a docstring that is based on numpy standards.
    

Complexity
****************

This library has been developed by using measures that help decreasing technical debt.
Developing software with low(er) technical dept may take extra development time, but has many advantages:

* Higher quality code
* easier maintanable
* Less prone to bugs and errors
* Higher security


Unit tests
****************


The use of unit tests is essential to garantee a consistent output of developed functions.
The following tests are secured using :func:`tests.test_ismember`:

* The input are checked.
* The output values are checked and whether they are encoded properly.
* The check of whether parameters are handled correctly.



.. raw:: html

	<hr>
	<center>
		<script async type="text/javascript" src="//cdn.carbonads.com/carbon.js?serve=CEADP27U&placement=erdogantgithubio" id="_carbonads_js"></script>
	</center>
	<hr>
