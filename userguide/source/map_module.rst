Map Module
==========

The Map application module is the foundation module of WebGIS as a GIS web-mapping visualization software.
The main functionalities provided by the Map application include:

* Providing easy navigation over maps of a defined area of interest.
* Visualizing various geo-spatial data and meteorological products on a projected map.
* Organizing the different mapped GIS data as layers and providing user-friendly interactivity for managing and customizing their display.
* Providing different methods of rendering(such as isolines and filled-contours) of the data layers and geo-spatial data.

|
|
|
|
|
|
|
|
|
|
|
|
|

The Basics
**********

Layer Manager
-------------

The main components of the Map module consists of the **Layer Manager** and the **Main Data Display Pane**.
The Layer Manager is the component the user interacts with to control what data to display and how to display
on the Main Data Display Pane.

.. figure:: images/map_layermanager1.png
   :width: 300   

   Layer Manager with Advanced Query open and Layers List Box pre-loaded with the default layers, DEM and Bounding Box.


.. table:: Interface Description
   :widths: 8 50
   :align: left

   =========  ===========================================================
     no.      component description
   =========  ===========================================================
   **1**      **Layers List Box**
   **2**      **Product Type Selector**
   **3**      **Add Layer Button**
   **4**      **Apply Display Button**
   **5**      **AOI Selector & AOI Refresh Button**
   **6**      **Delete Layer Button**
   **7**      **Layer Up/Down Button**
   **8**      **Show All Layers Toggle**
   =========  ===========================================================


Main Data Display Pane
----------------------

The Main Data Display Pane is the display area on which mapped data are presented.
Upon first log-in, it is always displays a map of the default Area Of Interest since the Layer Manager is by default pre-loaded 
with the DEM layer corresponding to this default Area of Interest. To learn how to change the user default Area Of Interest, please see Chapter 3.

Panning and zooming over the Area Of Interest is provided to the user for easy navigation and observation of the map.
Scrolling the mouse wheel up and down allows zooming-in and out of the map region, while clicking-and-dragging on the map provides panning of the region.
Alternatively, you can use the Map Navigation Control located on the right side of the map for zooming and panning. Clicking on the + and - is zooming
in and out respectively and clicking on an arrow key is panning the map in the respective direction by one step.


Selecting Product Type
----------------------

The Map Module allows visualization of meteorlogical products on a map.
Many of the aviation products such as GRIB, SIGWX and OPMET can all be displayed using the Map module.

