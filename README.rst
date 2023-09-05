pyimzML
=======


Description
-----------
Original fork:
A parser for the imzML format used in imaging mass spectrometry. See specification
`here  <https://ms-imaging.org/wp-content/uploads/2009/08/specifications_imzML1.1.0_RC1.pdf>`_.
Designed for use with imzML version 1.1.0. Outputs data as python lists and dicts.

The parser is developed by `Alexandrov Team <http://www.embl.de/research/units/scb/alexandrov/index.html>`_ at EMBL Heidelberg.

New in this branch:
M2aia support for image dimensionaltiy

Installation
------------
Please use :


* ``$ pip install git+git://github.com/cKNUSPeR/pyimzML.git`` will install pyimzML from github.


**Dependency Notes**

* pyimzML has an optional dependency to `lxml <http://lxml.de/index.html>`_. If lxml is not installed, pyimzML will instead use the built-in cElementTree or ElementTree package.

**Testing**


Attribution
-----------

The pyimzml/ontology directory includes data derived from the following ontologies:

* `Units of measurement ontology <http://www.obofoundry.org/ontology/uo.html>`_ by George Gkoutos `CC-BY license <https://creativecommons.org/licenses/by/3.0/>`_
* `Mass spectrometry ontology <http://www.obofoundry.org/ontology/ms.html>`_ by `Gerhard Mayer et al. <https://pubmed.ncbi.nlm.nih.gov/23482073/>`_ `CC-BY license <https://creativecommons.org/licenses/by/3.0/>`_
* `Imaging MS controlled vocabulary <https://ms-imaging.org/wp/imzml/controlled-vocabulary/>`_

