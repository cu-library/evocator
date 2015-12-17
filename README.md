# ares_summon_item_search

Using Summon search results to prepopulate forms in Ares.

## Installation

If Ares' webroot is at `C:\inetpub\wwwroot\ares`, then you can use `movefiles.cmd` to move js and css files to the correct locations. 
To do so, right click on `movefiles.cmd` and select "Run as administrator..." 

You can also copy the two files manually. Copy `ares_summon_item_search.js` to the js folder. Copy `ares_summon_item_search.css` to the css folder.

Add this to the head of IRFArticle.html:
```html
<script language="javascript" src="js/ares_summon_item_search.js"></script>
```