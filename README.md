ezdebugbox
==========

Displays eZ Publish debug in a lightbox, allows you to filter debug output by level and adds an HTML inspector
This tool is a GreaseMonkey script that improves the display of the front-end eZPublish debug, Works with Firefox and Chrome.

The fonctionnalities :

    Deport the debug information in a popup and add a button to open or close it
    Summarizes the number of errors and the most severe level in the button 
    Add a filter level on the informations
    Adds a DOM inspector to view the templates used

Installation on Firefox :

    Install GreaseMonkey plugin : https://addons.mozilla.org/fr/firefox/addon/greasemonkey/
    Install this script

Installation on Chrome :

    Install Tampermonkey extension : https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo
    Install this script

Configure eZ Publish by changing site.ini.append.php :
    [DebugSettings]
    # To active the debugger
    DebugOutput=enabled
 
    [TemplateSettings]
    # To active the DOM Inspector
    Debug=enabled
