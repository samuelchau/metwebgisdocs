Graphical User Interface Overview
=================================

Logging In and Out
------------------

To access the WebGIS application, launch a browser from any computer connected to the same local network as the WebGIS server and open it with following URL:

.. code-block:: bash

   http://[hostname]/webgis

 
where ``[hostname]`` is to be replaced by the hostname or IP address of the WebGIS server. Any modern internet browser such as Firefox or Chrome is recommended.
When first opened with this URL, the browser will present you with Login page of WebGIS shown below.

.. figure:: images/gui_login.png 

   The WebGIS login page

To log in, enter the User Name and Password provided to you by the system adminstrator.
Optionally, select the language supported by the Graphical User interface, and click on the Login button.
The default is English if no selection is made.

Upon successful login, the application will bring you to the main application display as shown below.

.. figure:: images/gui_mainpage.png 

   The main page after logging in

The Logout button is located at the upper-right corner. Once you've finished your session with WebGIS, 
you should log out of the application by clicking on this button. 
User whose session is still active has to log out before they can log in again from a different client browser.
The login and logout times of an user is always being recorded by the application in the logs.  


Overview of the Main Display Window
-----------------------------------

Upon first logging in, the main display window as shown below will be presented. 
By default, it is the Map application module being displayed in the main display window after logging in.

.. figure:: images/gui_mainpage_numbered.png

   Main Display Window showing the Map module
   
.. table:: Interface Description
   :widths: 8 50
   :align: left

   =========  ===========================================================
     no.      component description
   =========  ===========================================================
   **1**      **UTC Time Clock**                                          
   **2**      **User Name Display**                                      
   **3**      **Logout Button**                                            
   **4**      **Area Of Interest Management Tool**
   **5**      **Data Verification Panel Toggle**
   **6**      **New Alert Panel Toggle**
   **7**      **Status Bar**
   **8**      **Application Module Selector**
   **9**      **Layer Manager**
   **10**     **Main Data Display Pane**
   =========  ===========================================================



