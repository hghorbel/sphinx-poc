Managing navigations
====================

Managing navigations is composed of various actions, such as copying,
editing, cutting, cloning, deleting, and adding existing nodes. There
are three navigation types available to PRODUCT users:

-  `Site
   navigation <#PLFUserGuide.AdministeringeXoPlatform.ManagingNavigations.SiteNavigation>`__

-  `Group
   navigation <#PLFUserGuide.AdministeringeXoPlatform.ManagingNavigations.GroupNavigation>`__

-  `User
   navigation <#PLFUserGuide.AdministeringeXoPlatform.ManagingNavigations.UserPageNavigation>`__

**Site navigation**

If you are the site administrator or granted the appropriate privileges
by the site administrator, you can execute some special actions related
to site nodes.

To open the navigation form of a site, you first need to select
EditSiteNavigation from the top navigation bar, then right-click your
desired node to open the drop-down menu.

    **Note**

    -  The users under the */platform/administrators* group can do
       actions related to the site navigation.

    -  The navigation of a site is created automatically when a site is
       created.

    -  The navigation will be deleted automatically after its site has
       been deleted.

**Group navigation**

Each group has only one page navigation. Only managers or users with the
\* membership role of the navigation group and users of the
administrators group can add/list/edit/delete the navigation or edit
properties.

To manage the group's page navigation, click |image0| Portal Group Sites
on the top navigation bar.

The **Group Navigation Management** page will appear.

**User navigation**

Actions related to the page navigation of users include adding a new
page, editing a page/page layout. These actions are based on Permission
Setting set to a page.

    **Note**

    The page navigation of a user will be created automatically when the
    user is created (registered).

    Only the user who is the owner of the user page navigation can edit
    it.

    No one can create a user page navigation so that no one can delete
    it. The navigation will be deleted automatically when its user is
    deleted.

Adding a new node
-----------------

Select Add New Node to create a node as a sub-node of the selected node.

-  If you want to create a new node at the root level of the portal,
   click |image1|, then right-click the empty space and select Add New
   Node;

-  Or, simply click Add Node.

The Add/Edit Page Node form appears.

Enter values in the Page Node Setting tab.

**In which:**

+--------------------------+--------------------------------------------------+
| Field                    | Description                                      |
+==========================+==================================================+
| Asterisk (\*)            | This mark next to each field means that it is    |
|                          | required to enter values in the field.           |
+--------------------------+--------------------------------------------------+
| Uri                      | An identification of the node that is            |
|                          | auto-created after the new node has been         |
|                          | created.                                         |
+--------------------------+--------------------------------------------------+
| Node Name                | The node name which must be unique. Only         |
|                          | alphabetic, numeric and underscore characters    |
|                          | are allowed with its length from 3 to 30         |
|                          | characters and without ANY SPACES.               |
+--------------------------+--------------------------------------------------+
| Extended label mode      | Ticks this checkbox to activate the extended     |
|                          | label mode for your page node's label. If this   |
|                          | checkbox is deselected, the Language field will  |
|                          | disappear.                                       |
+--------------------------+--------------------------------------------------+
| Language                 | Selects your desired language for the node label |
|                          | from the drop-down menu.                         |
+--------------------------+--------------------------------------------------+
| Label                    | The display name of the node on the screen in    |
|                          | the selected language. This field is not         |
|                          | required and may be changed. Its length must be  |
|                          | between 3 and 120 characters, including SPACES.  |
|                          | For example, if you want to create a French      |
|                          | label for your node, first select the Extended   |
|                          | Label Mode checkbox. Next, from the Language     |
|                          | drop-down list, select your desired language and |
|                          | enter your French label into the Label field.    |
+--------------------------+--------------------------------------------------+
| Visible                  | Enables the page and its node to be shown or     |
|                          | hidden at the navigation bar and sitemap.        |
+--------------------------+--------------------------------------------------+
| Show Publication Date    | Enables this node to be published for a given    |
|                          | period. Two fields, including Start Publication  |
|                          | Date and End Publication Date only display when  |
|                          | this option is checked.                          |
+--------------------------+--------------------------------------------------+
| Start Publication Date   | The start date and time to publish the node.     |
+--------------------------+--------------------------------------------------+
| End Publication Date     | The end date and time to publish the node.       |
+--------------------------+--------------------------------------------------+

    **Note**

    You can set date and time by clicking Start Publication Date and End
    Publication Date and selecting a date from the calendar pop-up.

    **Note**

    If a node is not visible (the "Visible" option is unchecked or the
    current time is not within publication period), it does not appear
    in any navigation or site map, but is still accessible via its URL.

Select a page for this node in the Page Selector tab if you want.

**In which:**

+--------------------------+--------------------------------------------------+
| Field                    | Description                                      |
+==========================+==================================================+
| Page Id                  | The identification string of the page which is   |
|                          | created automatically.                           |
+--------------------------+--------------------------------------------------+
| Name                     | The selected page's name.                        |
+--------------------------+--------------------------------------------------+
| Title                    | The selected page's title.                       |
+--------------------------+--------------------------------------------------+
| Create Page              | Creates a new page with the inputted name and    |
|                          | the title.                                       |
+--------------------------+--------------------------------------------------+
| Search and Select Page   | Searches and selects an existing page.           |
+--------------------------+--------------------------------------------------+
| Clear Page               | Removes the inputted page information in the     |
|                          | fields.                                          |
+--------------------------+--------------------------------------------------+

-  If you select Create Page, input the name and title for the page.

-  If you select Search and Select Page, you do not need to enter values
   in these fields. They are automatically recorded after you have
   selected an existing page from the Select Page form.

   |image2|

   This window lists all existing pages of **Portal** or **Group** with
   basic information for each page.

   You can select a page for creating a node by simply clicking
   |image3|, or search for a specific page as follows:

   **i.** Enter your page title into the Title field to search by title;

   Or, enter the site name into the Site Name field to search by the
   page's site name;

   Or, enter values into both fields to further limit your search
   results by both Title and Site Name.

   **ii.** Select the area in which you want to search into the Type
   field.

   **iii.** Click |image4| to perform your search. All pages matching
   your search criteria will be listed.

   **iv.** Click |image5| on the row of the page to select.

   After selecting a page, you will see the page details in the Page
   Selector form.

Select one icon in the Icon tab if you want.

Click Save to accept the new node page, or X to close the form.

    **Note**

    To select a page, you must be a member in the **Access Permission**
    or **Edit Permission** list of the selected pages. When the page
    type is 'User', you cannot select a page of other users.

    If you do not have the *Access* permission for any page in the list,
    please contact your administrator to get appropriate permissions.

Editing a node
--------------

Select Edit this Node from the drop-down menu to open the form with all
similar fields when you `add a new
node. <#PLFUserGuide.AdministeringeXoPlatform.ManagingNavigations.AddingNewNode>`__

Change values in the fields of the current node, except the Node Name.

Click Save to complete your changes.

Copying/Pasting a node
----------------------

These functions are used to reproduce a node in another place.

Select Copy Node from the drop-down menu.

Right-click the position you want to paste this node and select Paste
Node.

Click Save to accept your changes.

    **Note**

    Two same node names in the same place are NOT allowed.

Cloning a node
--------------

The **Clone Node** function allows you to copy a node. The difference
between **cloning** and **copying** a node is that the cloned node has
its own page with the same content as the selected node. Therefore,
there will be a new page that has the same name as the cloned node's
page shown in the pages list when you access the **Pages Management**
page.

Select Clone Node from the drop-down menu.

Right-click the position that you want to paste this node and select
Paste Node.

The cloned node will be reproduced in a new place.

Click Save to accept your changes.

Cutting a node
--------------

This function enables you to change the position of a specific node,
such as changing the page path.

Select Cut Node from the drop-down menu.

Select the position that you want to paste this node, then click Paste
Node.

Click Save to accept your change.

The cut node will be moved to your newly selected place.

    **Note**

    Two same node names in the same place are not allowed.

Deleting a node
---------------

This function is used to remove a node linking to a page. After the node
has been removed, the page has been still existing.

Select Delete Node from the drop-down menu.

Click **OK** in the confirmation message.

Click Save to accept your change.

Changing nodes order
--------------------

You can easily move the position of nodes up or down in the navigation
bar following these steps:

Select Move Up or Move Down from the drop-down menu.

Click Save to accept your changes.

.. |image0| image:: images/common/administration_navigation.png
.. |image1| image:: images/common/up_arrow_icon.png
.. |image2| image:: images/gatein/select_page_form.png
.. |image3| image:: images/common/select_icon.png
.. |image4| image:: images/common/search_icon.png
.. |image5| image:: images/common/select_icon.png
