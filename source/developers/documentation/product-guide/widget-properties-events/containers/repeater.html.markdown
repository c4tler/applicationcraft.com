---
old_url: repeater.htm
title: "Repeater"
active_menu_item: developers
class_name: developers
full_width: true
---


The Repeater Widget is a powerful container Widget which allows you to display large amounts of data in a grid type format, that is quick to set up, highly configurable, and allows almost any type of cosmetic effect you are looking for. Data can be taken from any Application Craft Query and the Widget manages caching and paging of the data.

You can do a lot with Repeaters using AC Javascript. Our [Videos](http://www.applicationcraft.com/developers/training-videos/widget-data/) page also has some good examples.

<table>
<tr>
<td width="172">
<a id="general"> </a> <b>General</b>

</td>
<td width="21">
</td>
<td width="754">
</td>
</tr>
<tr>
<td width="172">
Widget Class

</td>
<td width="21">
</td>
<td width="754">
Internal class name of the widget. - RepeaterContainer and  WiziCore_Widget_Container

</td>
</tr>
<tr>
<td width="172">
Name

</td>
<td width="21">
</td>
<td width="754">
This is the Widget name that is displayed when references are made to the Widget. You can choose any name that includes alphanumeric characters.

</td>
</tr>
<tr>
<td width="172">
Elements per page

</td>
<td width="21">
</td>
<td width="754">
Elements per Page sets the number of blocks the container will show on one page. If Scrolling is enabled, it will show this number of elements in a large enough space which can be scrolled. If Scrolling is not enabled, you must ensure that the requested number of elements fit in the container otherwise some data will not be displayed.

</td>
</tr>
<tr>
<td width="172">
Start Page

</td>
<td width="21">
</td>
<td width="754">
Controls which page is the first displayed

</td>
</tr>
</table>
<table>
<tr>
<td width="172">
<a id="database"> </a> <b>Database</b>

</td>
<td width="21">
</td>
<td width="754">
</td>
</tr>
<tr>
<td width="172">
Store in Database

</td>
<td width="21">
</td>
<td width="754">
Select to true to store the data from this field for reporting

</td>
</tr>
<tr>
<td width="172">
Allow Foreign App Writing

</td>
<td width="21">
</td>
<td width="754">
Select to true to allow other apps to write into the repeater and to allow writing out.

</td>
</tr>
<tr>
<td width="172">
Automatic Relationships

</td>
<td width="21">
</td>
<td width="754">
  Where you can set the relationships to other apps (see <a href="/developers/documentation/product-guide/advanced-features/data-storage-management/instance-linking">Relational Apps & Instance Linking)</a>

</td>
</tr>
</table>
<table>
<tr>
<td width="172">
<a id="layout"> </a> <b>Layout</b>

</td>
<td width="21">
</td>
<td width="754">
</td>
</tr>
<tr>
<td width="172">
X

</td>
<td width="21">
</td>
<td width="754">
Number of pixels from the left edge of the Page.

</td>
</tr>
<tr>
<td width="172">
Y

</td>
<td width="21">
</td>
<td width="754">
Number of pixels from the top edge of the Page.

</td>
</tr>
<tr>
<td width="172">
Sizes

</td>
<td width="21">
</td>
<td width="754">
  Where you can set the Width and Height of the widget. If a widget is within a Container in Vertical or Horizontal mode, then the widget can also be made to change size in response to the size of the display width and height See <a href="/developers/documentation/product-guide/content-and-app-layout/responsive-adaptive-fluid-design/sizes-property-dialog">'Sizes' Property Dialog</a>

</td>
</tr>
<tr>
<td width="172">
Z-Index

</td>
<td width="21">
</td>
<td width="754">
A number that indicates the imaginary layer that the Widget is in. If you imagine several Widgets all placed over one another, the top-most Widget has the highest Z-Index and the bottom most Widget has the lowest. You can adjust the Z-Index by changing the value. You can also use the right-click menu to adjust these in a friendlier way.

</td>
</tr>
<tr>
<td width="172">
Vertical Spacing

</td>
<td width="21">
</td>
<td width="754">
Controls the vertical pixel space between blocks

</td>
</tr>
<tr>
<td width="172">
Horizontal Spacing

</td>
<td width="21">
</td>
<td width="754">
Controls the horizontal pixel space between blocks

</td>
</tr>
<tr>
<td width="172">
Repeating Mode

</td>
<td width="21">
</td>
<td width="754">
There are four possible settings:

1) Vertical the blocks are displayed vertically

2) Horizontal, the blocks are displayed horizontally

3) Vertical first, the blocks are displayed vertically until the container is filled and then run horizontally

4) Horizontal first, the blocks are displayed horizontally until the container is filled and then run vertically See [Repeater Examples](repeater_examples.htm)

</td>
</tr>
<tr>
<td width="172">
Scrolling

</td>
<td width="21">
</td>
<td width="754">
If scrolling is set to true, then the data will be accessible by scrolling inside the container space. If scrolling is set to false, then only data that fits inside the container will be displayed.

</td>
</tr>
<tr>
<td width="172">
Stretching

</td>
<td width="21">
</td>
<td width="754">
</td>
</tr>
<tr>
<td width="172">
Separating Lines

</td>
<td width="21">
</td>
<td width="754">
This property works with the Line Width and Line Color properties in the Style property section. If set to true, a line will be displayed between blocks.

</td>
</tr>
<tr>
<td width="172">
Hide Last Line

</td>
<td width="21">
</td>
<td width="754">
Sometimes the line at the bottom of the container can look messy next to the container. This property allows you to have separating lines without the bottom line clashing with the container.

</td>
</tr>
<tr>
<td width="172">
Align in Container

</td>
<td width="21">
</td>
<td width="754">
Left/Center/Right. Set as required to align the widget within its parent container

</td>
</tr>

</table>
<table>
<tr>
<td width="172">
<a id="behavior"> </a> <b>Behavior</b>

</td>
<td width="21">
</td>
<td width="754">
</td>
</tr>
<tr>
<td width="172">
Drag and Drop

</td>
<td width="21">
</td>
<td width="754">
If set to true, the user is able to drag and drop the widget with the mouse at run time

</td>
</tr>
<tr>
<td width="172">
Resizing

</td>
<td width="21">
</td>
<td width="754">
Disable/Enable. Set to True to allow the widget to be resized at Runtime. Configurable Max/Min Width and Height, Right & Bottom, Top & Left or All

</td>
</tr>
<tr>
<td width="172">
Visible

</td>
<td width="21">
</td>
<td width="754">
Set to False if you want the Widget to appear hidden by default. You would use Javascript to override this at a later stage.

</td>
</tr>
<tr>
<td width="172">
Read only

</td>
<td width="21">
</td>
<td width="754">
If set to True, the object can be interacted with by a user but data cannot be altered.

</td>
</tr>
<tr>
<td width="172">
Enable

</td>
<td width="21">
</td>
<td width="754">
Set to false to leave the Widget visible but to prevent any user interaction

</td>
</tr>
</table>
<table>
<tr>
<td width="172">
<a id="data"> </a> <b>Data</b>

</td>
<td width="21">
</td>
<td width="754">
  See <a href="repeater_data.htm">Repeater Data</a>

</td>
</tr>
<tr>
<td width="172">
View

</td>
<td width="21">
</td>
<td width="754">
Select the view to use

</td>
</tr>
<tr>
<td width="172">
Fields

</td>
<td width="21">
</td>
<td width="754">
  This property is used to allow you to set which data fields are taken from the View and used in the Widget. Read the <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/fields/">Fields</a> section for more details.

</td>
</tr>
<tr>
<td width="172">
Group By

</td>
<td width="21">
</td>
<td width="754">
  This allows you to Group data within a View in the same way you would with a SQL statement. Read the <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/fiieldsgroup-by">Group By</a> section for more details.

</td>
</tr>
<tr>
<td width="172">
Order By

</td>
<td width="21">
</td>
<td width="754">
  Specifies the order in which data is presented to the Widget.  Read the <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/order-by">Order By</a> section for more details.

</td>
</tr>
<tr>
<td width="172">
Filter

</td>
<td width="21">
</td>
<td width="754">
This is a global, static filter that can be defined for each View in your App.

</td>
</tr>
<tr>
<td width="172">
Listen

</td>
<td width="21">
</td>
<td width="754">
  This indicates whether the Widget should react to a Drill Down action on a common View. Read the <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/listen">Listen</a> section for more details.

</td>
</tr>
<tr>
<td width="172">
Auto Load

</td>
<td width="21">
</td>
<td width="754">
Set to true to automatically fetch data from assigned view.

</td>
</tr>
<tr>
<td width="172">
Key Fields

</td>
<td width="21">
</td>
<td width="754">
Set to map View fields. For use in writing data back out to connected database tables

</td>
</tr>
</table>
<table>
<tr>
<td width="172">
<a id="style"> </a> <b>Style</b>

</td>
<td width="21">
</td>
<td width="754">
</td>
</tr>
<tr>
<td width="172">
Border

</td>
<td width="21">
</td>
<td width="754">
Controls Border for whole container, using Border dialog

</td>
</tr>
<tr>
<td width="172">
Border Radius

</td>
<td width="21">
</td>
<td width="754">
Controls the radius size of curved border edges

</td>
</tr>
<tr>
<td width="172">
Margin

</td>
<td width="21">
</td>
<td width="754">
  Used to specify the margin around a widget when the parent container is in Relative Mode. See <a href="/developers/documentation/product-guide/content-and-app-layout/introduction/setting-a-margin">Setting a Margin</a>

</td>
</tr>
<tr>
<td width="172">
BG Color

</td>
<td width="21">
</td>
<td width="754">
Controls BG Color of whole container

</td>
</tr>
<tr>
<td width="172">
Block BG Color

</td>
<td width="21">
</td>
<td width="754">
Controls BG Color of Alternate Blocks. Blocks 1,3,5 etc. NOTE: If you want to change all blocks you must edit both this and the alternative block colors

</td>
</tr>
<tr>
<td width="172">
Block Alternative BG Color

</td>
<td width="21">
</td>
<td width="754">
Controls BG Color of Alternate Blocks. Blocks 2,4,6 etc.

</td>
</tr>
<tr>
<td width="172">
Block Border

</td>
<td width="21">
</td>
<td width="754">
Controls Border of Blocks NOTE: If you want to border all blocks you must edit this property and Block Alternative Border property

</td>
</tr>
<tr>
<td width="172">
Block Alternative Border

</td>
<td width="21">
</td>
<td width="754">
Controls Border of Alternate Blocks

</td>
</tr>
<tr>
<td width="172">
Block Border Radius

</td>
<td width="21">
</td>
<td width="754">
Controls the radius size of curved block edges

</td>
</tr>
<tr>
<td width="172">
Block Alternative Border Radius

</td>
<td width="21">
</td>
<td width="754">
Controls the radius size of alternate curved block edges

</td>
</tr>
<tr>
<td width="172">
Line Width

</td>
<td width="21">
</td>
<td width="754">
Controls the separating line width

</td>
</tr>
<tr>
<td width="172">
Line Color

</td>
<td width="21">
</td>
<td width="754">
Controls the separating line color

</td>
</tr>
<tr>
<td width="172">
BG Image

</td>
<td width="21">
</td>
<td width="754">
This specifies a background image to your Container

</td>
</tr>
<tr>
<td width="172">
BG Repeat

</td>
<td width="21">
</td>
<td width="754">
This specifies how a BG Image can repeat behind your Container (Repeat, Repeat X, Repeat Y)

</td>
</tr>
<tr>
<td width="172">
Opacity

</td>
<td width="21">
</td>
<td width="754">
This % value specifies the transparency of the Widget.

</td>
</tr>
<tr>
<td width="172">
Display Hourglass Over

</td>
<td width="21">
</td>
<td width="754">
Inherit(default)/Widget/Whole App. Select Widget if you wish to present a custom hourglass over this widget

</td>
</tr>
<tr>
<td width="172">
Hourglass Animation

</td>
<td width="21">
</td>
<td width="754">
Where you can override the default hourglass image to an image of your Resources or 'None' where no hourglass is shown when Display Hourglass Over property is set to Widget

</td>
</tr>
<tr>
<td width="172">
Custom CSS Classes

</td>
<td width="21">
</td>
<td width="754">
  Where you define your CSS Style to customise your widgets  See also <a href="/developers/documentation/product-guide/advanced-features/custom-css-classes/">Custom CSS Classes</a>

</td>
</tr>
<tr>
<td width="172">
Widget Style

</td>
<td width="21">
</td>
<td width="754">
  This refers to the <a href="/developers/documentation/product-guide/content-and-app-layout/introduction/themes-styles/themesmanage">Theme entry</a> that should be used to set the Widget's default appearance. Once a Theme Style has been selected, individual components such as Font and Colors can be Set to False if you want the Widget to appear hidden by default.

</td>
</tr>
</table>

Repeater:

<table>
<tr>
<td width="149">
  <strong>Supported Events:</strong>

</td>
<td width="21">
</td>
<td width="121">
</td>
</tr>
<tr>
<td width="149">
  <a href="/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/general-events">General Events</a>

</td>
<td width="21">
</td>
<td width="121">
  <a href="/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/data-events">Data Events</a>

</td>
</tr>
<tr>
<td width="149">
On Row Loaded

</td>
<td width="21">
</td>
<td width="121">
On Data Loaded

</td>
</tr>
<tr>
<td width="149">
</td>
<td width="21">
</td>
<td width="121">
On Data Reset

</td>
</tr>
</table>

Repeater Container:

<table>
<tr>
<td width="148">
  <strong>Supported Events:</strong>

</td>
<td width="17">
</td>
<td width="128">
</td>
</tr>
<tr>
<td width="148">
  <a href="/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/mouse-events">Mouse Events</a>

</td>
<td width="17">
</td>
<td width="128">
  <a href="/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/data-events">Data Events</a>

</td>
</tr>
<tr>
<td width="148">
On Click

</td>
<td width="17">
</td>
<td width="128">
On Data Loaded

</td>
</tr>
<tr>
<td width="148">
On Double Click

</td>
<td width="17">
</td>
<td width="128">
</td>
</tr>
<tr>
<td width="148">
On Mouse Down

</td>
<td width="17">
</td>
<td width="128">
</td>
</tr>
<tr>
<td width="148">
On Mouse Up

</td>
<td width="17">
</td>
<td width="128">
</td>
</tr>
<tr>
<td width="148">
On Mouse Enter

</td>
<td width="17">
</td>
<td width="128">
</td>
</tr>
<tr>
<td width="148">
On Mouse Leave

</td>
<td width="17">
</td>
<td width="128">
</td>
</tr>
<tr>
<td width="148">
On Drag Start

</td>
<td width="17">
</td>
<td width="128">
</td>
</tr>
<tr>
<td width="148">
On Drag Stop

</td>
<td width="17">
</td>
<td width="128">
</td>
</tr>
<tr>
<td width="148">
On Resize Start

</td>
<td width="17">
</td>
<td width="128">
</td>
</tr>
<tr>
<td width="148">
On Resize Stop

</td>
<td width="17">
</td>
<td width="128">
</td>
</tr>
</table>

## See Also

 - [Mouse Events](/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/mouse-events)
 - [General Events](/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/general-events)
 - [Data Events](/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/data-events)
 - [Repeater & Grid Object functions](/developers/documentation/scripting-apis/client-api/widget-object-functions/repeater-grid/)
