# UmbracoDuplicateContent
This is a simple App plugin that adds a context menu item to content nodes which will allow you to duplicate that node (up to 20 times) within the current parent node. I created it as I find when setting up sites I dummy populate by creating 1 fully populated page and then copying it, however the Umbraco copy function requires a lot of clicks. This package will also let you over ride the default copy name with a Lorem Ipsum alternative.
I have tested this project on some local builds and all it does is add a .dll to your bin and a plugin folder to your App_Plugins, however I would always err on the site of caution and test this package out prior to releasing onto a live site.

You can download it here, or install fro mthe Umbraco package library:
https://our.umbraco.org/projects/backoffice-extensions/duplicate-content/

or use NuGet:
Install-Package CP.UmbracoDuplicateContent
