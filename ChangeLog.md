## Version 0.4 - 10 Mar 10 ##
### Manager ###
  * Customizable size for the popup. Change it in the options page.
  * Added three icons to the popup: Open options, open reading list in new window, and open RIL Digest in new tab.
### Adder ###
  * One click add mode! Turn it on in the options page. Now you can add items to your reading list with only one click. No more click to open > click to save > click to close! (Only works on address bar, not Google Reader yet.)
  * Issues with GReader keyboard shortcuts not working after clicking the Postponer icon SHOULD be fixed now. Please let me know if you're still having this issue.

## Version 0.3.1 - 8 Feb 10 ##
### Adder-only update ###
  * Fixed keyboard shortcut issue after clicking icon in Google Reader

## Version 0.3 - 4 Feb 10 ##
### Manager ###
  * Now badge only reloads when Chrome is opened and when the icon is clicked. Previous version was running out of API calls within seconds and overloading the RIL server. Sorry! Just remember to click the icon to reload.
### Adder ###
  * Google Reader integration! Now an icon appears next to the title of articles in Google Reader. When clicked, a window appears to add the item to RIL. Clicking this icon also reloads the badge in the Manager.
  * Options page to turn Google Reader integration on/off, change the position of the icon to before or after the title of the article, and whether to show the icon in list view, expanded view, or both.

## Version 0.2 - 23 Dec 09 ##
### Manager ###
  * Added title to browser action icon
  * Icon can now show number of unread items in a badge
  * Added an options page for enabling badge and checking credentials
  * Added scheduling for badge reload when icon in clicked and external reload request (ie, from Postponer Adder) is sent

### Adder ###
  * Added communication with Manager so badge is scheduled to reload when Adder icon is clicked.

## Version 0.1 - 22 Dec 09 ##
  * Initial release