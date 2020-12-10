Tests with T--structures
**********************************

* Vessel parameters

  * Ship name: HOEGH VERLIN
  * Ship Type: VE
  * Length: 228 m
  * Breadth: 32 m
  * Draft: 8.5 m (avg), 13.3 m (max)
  * Speed: 20.9 knots (max), 12.1 (avg)
  * Sailing Direction: South
  * Date of record: 6/30/18 0:59:22 duration of measurement 3.47 hrs

* Hydrodynamic conditions

  * Tide: 0.9751 m (NAVD88) (to test maximum effect we used 0.0 m)
  * Tidal current: 0.028 m/s (we did not use the background current)
  * Wind: 1.6 m/s, 1.8 m/s gust, direction of 242 deg  (we did not use wind forcing)

* Computational grid and T-structure setup

.. figure:: images/grid_struc.jpg
    :align: center
    :width: 400px
    :figclass: align-center 

    Figure: Computational grid. Dimensions: 2399 x 2799. DX = 1.34144, DY = 1.71597 (1/18 arc-sec)

.. figure:: images/dep_struc_zoom.jpg
    :align: center
    :width: 350px
    :height: 500px
    :figclass: align-center 

    Figure: T-structures resolved in the grid.

.. figure:: images/T_structures.jpg
    :align: center
    :height: 400px
    :figclass: align-center  

    Figure: T-structures from the measurement.

* Animation of a test with a large-scale ship:  LOEGH BERLIN 

.. raw:: html

    <iframe width="720" height="410" src="https://www.youtube.com/embed/MhGV9lvBSoU?rel=0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

* Download animation file `Click here <https://drive.google.com/file/d/1szwlLTWMgH9qAa7IXppJpulx7GS6HjGg/view?usp=sharing>`_

* Comparison of maximum elevation with/without structures

.. figure:: images/hmax_10ms_ns.jpg
    :align: center
    :figclass: align-center  

    Figure: Maximum elevation.

* Comparison of maximum velocity with/without structures

.. figure:: images/umax_10ms_ns.jpg
    :align: center
    :figclass: align-center  

    Figure: Maximum velocity.








