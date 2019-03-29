Statistics
==========

Use this screen to manage statistics. A fresh OTRS installation already contains some statistics by default. The statistics management screen is available in the *Statistics* menu item of the *Reports* menu.

.. figure:: images/statistics-overview.png
   :alt: Statistics Overview Screen

   Statistics Overview Screen


Manage Statistics
-----------------

Three type of statistics are available in OTRS.

.. figure:: images/statistics-add.png
   :alt: Add Statistics Screen

   Add Statistics Screen

Dynamic Matrix
   Each cell contains a singular data point.

Dynamic List
   Each row contains data of one entity.

Static
   Non-configurable complex statistics.

To create a new statistics:

1. Click on the *Add Statistics* button in the left sidebar.
2. Select the type for the new statistics.
3. Fill in the required fields.
4. Click on the *Save* button.

.. figure:: images/statistics-add-general-specification.png
   :alt: Add General Specification Section

   Add General Specification Section

To edit a statistics:

1. Click on a statistics number in the list of statistics.
2. Modify the fields and the statistics details.
3. Click on the *Save* or *Save and finish* button.

.. figure:: images/statistics-edit-general-specification.png
   :alt: Edit General Specification Section

   Edit General Specification Section

To import a statistics:

1. Click on the *Import Statistics* button in the left sidebar.
2. Click on the *Browse…* button and select a previously exported ``.xml`` file.
3. Click on the *Import* button.
4. Modify the fields and the statistics details.
5. Click on the *Save* or *Save and finish* button.

.. figure:: images/statistics-import.png
   :alt: Import Statistics Configuration Screen

   Import Statistics Configuration Screen

To export a statistics:

1. Click on the download icon in list of statistics.
2. Choose a location in your computer to save the ``.xml`` file.

To delete a statistics:

1. Click on the trash icon in the list of statistics.
2. Click on the *OK* button in the confirmation screen.

To run a statistics:

1. Click on the play icon in list of statistics.
2. Review the statistics details.
3. Click on the *Run now* button.

.. figure:: images/statistics-run-now.png
   :alt: View Statistics Screen

   View Statistics Screen

To preview a statistics:

1. Go the the edit screen of a statistics.
2. See the preview.
3. Change the settings to view different type of graphs.
4. Change the values of *X-axis*, *Y-axis* and *Filter* with the respective buttons.

.. figure:: images/statistics-preview.png
   :alt: Statistics Preview Widget

   Statistics Preview Widget

.. note::

   The preview uses random data and does not consider data filters.


General Statistics Specification
--------------------------------

The following settings are available when adding or editing this resource. The fields marked with an asterisk are mandatory.

Title \*
   The name of this resource. Any type of characters can be entered to this field including uppercase letters and spaces. The name will be displayed in the overview table.

Description
   Add additional information to this resource. It is recommended to always fill this field as a description of the resource with a full sentence for better clarity, because the comment will be also displayed in the overview table.

Permissions \*
   You can select one or more groups to define access for different agents.

Result formats \*
   You can select, in which format should be able to see the statistics.

Time Zone \*
   The selected time periods in the statistics are time zone neutral.

Create summation row
   Generate an additional row containing sums for all data rows.

Create summation column
   Generate an additional column containing sums for all data columns.

Cache results
   Stores statistics result data in a cache to be used in subsequent views with the same configuration (requires at least one selected time field).

Show as dashboard widget
   Provide the statistics as a widget that agents can activate in their dashboard.

   .. note::

      Enabling the dashboard widget will activate caching for this statistics in the dashboard.

Validity \*
   Set the validity of this resource. Each resource can be used in OTRS only, if this field is set to *valid*. Setting this field to *invalid* will disable the use of the resource.
