.. index:: Wirkungsgrad
.. _Wirkungsgrad:

Wirkungsgrad
============

Sofern bei einem mechanischen Prozess die stets auftretende Reibung sehr klein
gehalten werden kann, so ist es möglich, sie bei der Formulierung von
physikalischen Gesetzen unberücksichtigt zu lassen. Bei genauer Betrachtung
zeigt sich allerdings, dass die von einer mechanischen Einrichtung aufgenommene
Arbeit stets größer ist als die von ihr abgegebene Arbeit. Es scheint also
Arbeit verloren gegangen zu sein, der Satz von der Erhaltung der mechanischen
Arbeit scheint somit seine Geltung zu verlieren.

.. figure::
    ../../pics/mechanik/arbeit-energie-leistung/wirkungsgrad-energiefluss-diagramm.png
    :name: fig-wirkungsgrad-energiefluss-diagramm
    :alt:  fig-wirkungsgrad-energiefluss-diagramm
    :align: center
    :width: 50%

    Wirkungsgrad eines mechanischen Prozesses ("Energiefluss-Diagramm").

    .. only:: html

        :download:`SVG: Wirkungsgrad ("Energiefluss-Diagramm")
        <../../pics/mechanik/arbeit-energie-leistung/wirkungsgrad-energiefluss-diagramm.svg>`

.. _Effizienz:

Tatsächlich verschwindet die verrichtete Arbeit allerdings nicht, sondern es
wird stets eine entsprechend große Menge an Reibungsarbeit verrichtet. Das
Gesetz von der Erhaltung der mechanischen Arbeit kann -- unter Berücksichtigung
der Reibung -- somit folgendermaßen formuliert werden: [#]_

.. math::

    \text{Aufgenommene Arbeit = Abgegebene Arbeit + Reibungsarbeit}

*Definition:*

    Das Verhältnis aus der abgegebenen Arbeit :math:`W_{\mathrm{out}}` und der
    aufgenommenen Arbeit :math:`W_{\mathrm{in}}` wird Wirkungsgrad :math:`\eta`
    einer mechanischen Einrichtung genannt:

.. math::
    :label: eqn-wirkungsgrad

    \eta = \frac{W_{\mathrm{out}}}{W_{\mathrm{in}}}

*Einheit:*

    Als Verhältniszahl hat der Wirkungsgrad keine Einheit. Er ist umso größer,
    je geringer die Reibungsarbeit ist. Ist überhaupt keine Reibung vorhanden,
    so ergibt sich der Wert :math:`\eta = 1`, da in diesem Fall der Zähler und
    der Nenner auf der rechten Seite der Gleichung übereinstimmen.

Da sich -- abgesehen von in Vakuum stattfindenden Prozessen -- Reibung niemals
komplett beseitigen lässt, gibt es keine mechanische Einrichtung mit einem
Wirkungsgrad :math:`\eta~=~1`. Durch gutes Ölen und Schmieren ist es allerdings
möglich, diesen Wert zumindest annähernd zu erreichen. Ein hoher Wirkungsgrad,
der nur geringfügig kleiner als :math:`1` ist, bedeutet, dass der größte Teil
der aufgenommenen Arbeit als abgegebene mechanische Arbeit wirksam ist.

Besteht eine mechanische Einrichtung aus mehreren Komponenten, die jeweils die
Wirkungsgrade :math:`\eta_1,\, \eta_2,\, \ldots` haben, so ergibt sich für den
Gesamt-Wirkungsgrad :math:`\eta_{\mathrm{Ges}}` der Anlage:

.. math::

    \eta_{\mathrm{Ges}} = \frac{W_{\mathrm{out}}}{W_{\mathrm{in}}}= \eta_1 \cdot
    \eta_2 \cdot \ldots

Der Gesamt-Wirkungsgrad einer mechanischen Einrichtung ist wegen :math:`\eta \le
1` somit kleiner als der Wirkungsgrad der am wenigsten effizienten Komponente.

.. raw:: html

    <hr />

.. only:: html

    .. rubric:: Anmerkungen:

.. [#] Eine noch allgemeinere Formulierung dieser Aussage stellen die so
    genannten :ref:`Hauptsätze der Wärmelehre <Hauptsätze der Wärmelehre>` dar.

.. raw:: html

    <hr />

.. hint::

    Zu diesem Abschnitt gibt es :ref:`Übungsaufgaben <Aufgaben Wirkungsgrad>`.

