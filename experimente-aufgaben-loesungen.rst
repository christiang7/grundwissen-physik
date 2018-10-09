.. _Aufgaben und Lösungen:
.. _Experimente, Übungsaufgaben und Lösungen:

Experimente, Übungsaufgaben und Lösungen
========================================

.. Anzahl der Aufgaben beziehungsweise  Experimente ausgeben:

.. find ./ -name "*aufgaben*.rst"    | xargs grep -c "^\* "         | awk -F ":" '{sum+=$2} END {print sum}'
.. find ./ -name "*loesungen*.rst"   | xargs grep -c "^\* "         | awk -F ":" '{sum+=$2} END {print sum}'
.. find ./ -name "*experimente*.rst" | xargs grep -c ".. rubric:: " | awk -F ":" '{sum+=$2} END {print sum}'

..  Now 2016-05-16

.. *  68 Experimente, 17 Bilder
.. * 141 Übungsufgaben
.. * 141 Lösungen

.. _Experimente:

Experimente
-----------

.. only:: html

    .. sidebar:: Hinweis

        Eine Vorlage eines Versuch-Protokolls kann hier als
        :download:`PDF-Dokument <versuchsprotokoll.pdf>` heruntergeladen werden.

.. only:: latex

    Eine Vorlage eines Versuch-Protokolls kann auf der `Grund-Wissen-Webseite
    <file:///home/waldgeist/data/homepage/grund-wissen/physik/_build/html/experimente-aufgaben-loesungen.html>`__
    als PDF-Datei heruntergeladen werden.

..  Experimente sind in der Physik von besonderer Bedeutung. Mit einem geeigneten
..  Versuchsaufbau können Ursache-Wirkungs-Zusammenhänge anschaulich und
..  beliebig oft wiederholbar untersucht werden.

.. toctree::
    :maxdepth: 2

    mechanik/experimente.rst
    akustik/experimente.rst
    optik/experimente.rst
    waermelehre/experimente.rst
    elektrizitaet-und-magnetismus/experimente.rst


.. _Aufgaben:
.. _Übungsaufgaben:

Übungsaufgaben
--------------

.. toctree::
    :maxdepth: 2

    mechanik/aufgaben.rst
    optik/aufgaben.rst
    waermelehre/aufgaben.rst
    elektrizitaet-und-magnetismus/aufgaben.rst
    atomphysik/aufgaben.rst


.. _Lösungen:

Lösungen
--------

.. toctree::
    :maxdepth: 2

    mechanik/loesungen.rst
    optik/loesungen.rst
    waermelehre/loesungen.rst
    elektrizitaet-und-magnetismus/loesungen.rst
    atomphysik/loesungen.rst

