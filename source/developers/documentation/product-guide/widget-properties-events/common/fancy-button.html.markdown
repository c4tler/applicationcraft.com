---
old_url: fancy_button.htm
title: "Fancy Button"
active_menu_item: developers
class_name: developers
full_width: true
---


The Fancy Button allows you to define shapes, gradient colors when pressed, as well as be used to manage Data views and Page Navigation, but also can be used to trigger [Events](/developers/documentation/product-guide/widget-properties-events/events/) using [Scripting with Javascript](/developers/documentation/scripting-apis/client-scripting-overview/scripting-with-javascript/)

A range of options are available to be set:

![fancyButton](/img/docs/fancybutton.zoom72.png)

<table>
<tr>
<td width="148">
<a id="general"> </a> <b>General</b>

</td>
<td width="15">
</td>
<td width="779">
</td>
</tr>
<tr>
<td width="148">
Widget Class

</td>
<td width="15">
</td>
<td width="779">
Internal class name of the widget.- FancyButton

</td>
</tr>
<tr>
<td width="148">
Name

</td>
<td width="15">
</td>
<td width="779">
This is the Widget name that is displayed when references are made to the Widget. You can choose any name that includes alphanumeric characters.

</td>
</tr>
<tr>
<td width="148">
Link

</td>
<td width="15">
</td>
<td width="779">
Dial/Email/SMS/URL. Define a link from the widget. For Email/SMS/URL additional parameters (Subject/Body etc) can also be set. Dial & SMS for use with Mobile apps. See also: <a href="/developers/documentation/scripting-apis/client-api/app-functions/mobiledial">mobileDial()</a> , <a href="/developers/documentation/scripting-apis/client-api/app-functions/mobileemail">mobileEmail()</a> , <a href="/developers/documentation/scripting-apis/client-api/app-functions/mobilesms">mobileSMS()</a>

</td>
</tr>
<tr>
<td width="148">
Page Jump

</td>
<td width="15">
</td>
<td width="779">
Select to set the page to jump to. ('Forward' and 'Back' behave in same manner as in a browser)

</td>
</tr>
<tr>
<td width="148">
Options

</td>
<td width="15">
</td>
<td width="779">
Where you can set the button properties - Shape/Image/Text/pushEffect/Sticky/Fill/Image etc. See above

</td>
</tr>
</table>
<table>
<tr>
<td width="148">
<a id="layout"> </a> <b>Layout</b>

</td>
<td width="15">
</td>
<td width="779">
</td>
</tr>
<tr>
<td width="148">
X

</td>
<td width="15">
</td>
<td width="779">
Number of pixels from the left edge of the Page.

</td>
</tr>
<tr>
<td width="148">
Y

</td>
<td width="15">
</td>
<td width="779">
Number of pixels from the top edge of the Page.

</td>
</tr>
<tr>
<td width="148">
Width

</td>
<td width="15">
</td>
<td width="779">
Width of the Widget in pixels.

</td>
</tr>
<tr>
<td width="148">
Height

</td>
<td width="15">
</td>
<td width="779">
Height of the Widget in pixels.

</td>
</tr>
<tr>
<td width="148">
Repeat

</td>
<td width="15">
</td>
<td width="779">
If set to True, this displays the Widget on either all pages except ones you specify in a list or only on pages you choose from a list.  Find out more about this in <a href="/developers/documentation/product-guide/content-and-app-layout/editing-and-laying-out-reference/repeating-widgets-across-multi">Repeating Widgets Across Multiple Pages</a> .

</td>
</tr>
<tr>
<td width="148">
Z-Index

</td>
<td width="15">
</td>
<td width="779">
A number that indicates the imaginary layer that the Widget is in. If you imagine several Widgets all placed over one another, the top-most Widget has the highest Z-Index and the bottom most Widget has the lowest. You can adjust the Z-Index by changing the value. You can also use the right-click menu to adjust these in a friendlier way.

</td>
</tr>
<tr>
<td width="148">
Anchors

</td>
<td width="15">
</td>
<td width="779">
This is used in conjunction with "Docked" App Pages. You can use this to allows a Widget's X, Y, Width and Height to be automatically altered as the browser window is resized. See <a href="/developers/documentation/product-guide/content-and-app-layout/editing-and-laying-out-reference/widget-anchoring">Docking & Anchoring</a> .

</td>
</tr>
<tr>
<td width="148">
Align in Container

</td>
<td width="15">
</td>
<td width="779">
Left/Center/Right. Set as required to align the widget within its parent container

</td>
</tr>
<tr>
<td width="148">
Tab Order

</td>
<td width="15">
</td>
<td width="779">
Where you can control the tab order in your app.

</td>
</tr>
<tr>
<td width="148">
Tab Stop

</td>
<td width="15">
</td>
<td width="779">
true/false.  If set to false users will not tab into this field

</td>
</tr>
</table>
<table>
<tr>
<td width="148">
<a id="behavior"> </a> <b>Behavior</b>

</td>
<td width="15">
</td>
<td width="779">
</td>
</tr>
<tr>
<td width="148">
Visible

</td>
<td width="15">
</td>
<td width="779">
Set to False if you want the Widget to appear hidden by default. You would use Javascript to override this at a later stage.

</td>
</tr>
<tr>
<td width="148">
Enable

</td>
<td width="15">
</td>
<td width="779">
Set to false to leave the Widget visible but to prevent any user interaction.

</td>
</tr>
</table>
<table>
<tr>
<td width="148">
<a id="style"> </a> <b>Style</b>

</td>
<td width="15">
</td>
<td width="779">
</td>
</tr>
<tr>
<td width="148">
Opacity

</td>
<td width="15">
</td>
<td width="779">
This % value specifies the transparency of the Widget.

</td>
</tr>
<tr>
<td width="148">
Margin

</td>
<td width="15">
</td>
<td width="779">
Used to specify the margin around a widget when the parent container is in Relative Mode. See <a href="/developers/documentation/product-guide/content-and-app-layout/introduction/setting-a-margin">Setting a Margin</a>

</td>
</tr>
<tr>
<td width="148">
Custom CSS Styles

</td>
<td width="15">
</td>
<td width="779">
Where you define your CSS Style to customise your widgets  See also <a href="/developers/documentation/product-guide/advanced-features/custom-css-classes/">Custom CSS Classes</a>

</td>
</tr>
<tr>
<td width="148">
Widget Style

</td>
<td width="15">
</td>
<td width="779">
This refers to the <a href="/developers/documentation/product-guide/content-and-app-layout/introduction/themes-styles/themesmanage">Theme entry</a> that should be used to set the Widget's default appearance. Once a Theme Style has been selected, individual components such as Font and Colors can be Set to False if you want the Widget to appear hidden by default.

</td>
</tr>
</table>

<table>
<tr>
<td width="148">
  <strong>Supported Events:</strong>

</td>
</tr>
<tr>
<td width="148">
  <a href="/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/mouse-events">Mouse Events</a>

</td>
</tr>
<tr>
<td width="148">
On Click

</td>
</tr>
<tr>
<td width="148">
On Double Click

</td>
</tr>
<tr>
<td width="148">
On Mouse Down

</td>
</tr>
<tr>
<td width="148">
On Mouse Up

</td>
</tr>
<tr>
<td width="148">
On Mouse Enter

</td>
</tr>
<tr>
<td width="148">
On Mouse Leave

</td>
</tr>
</table>

## See Also

 - Mobile Widgets: [Action Button](/developers/documentation/product-guide/widget-properties-events/mobile/mobaction-button)

 - Common Widgets: [Action Button](/developers/documentation/product-guide/widget-properties-events/common/action-button)
 - [Mouse Events](/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/mouse-events)

