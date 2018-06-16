# BlankSheets
Android app for Morning pages.
TODO add wiki

See: http://juliacameronlive.com/basic-tools/morning-pages/

## Behaviour

### For now:
First screen is a list of written pages and "add page" button.
Add page leads user to screen for creating new morning page. This should be auto saved while typing / on pause, and it should count words as well as show some indication of how far along the page user is.

### Some day:
- User should not be encouraged to read previous morning pages (maybe only recent).
Some statistics should be on the first page, and maybe some recent pages.
- Statistics: words used, words written...
- Widget for adding a new page
- Autosync
- Notification

## App architecture, for when I don't work on it for one month and forget everything.
### First screen:
List of written pages uses RecyclerView. This RecyclerView will use an adapter to adapt cursor rows to cards.<br/>
<b>Card</b> = tiny representation of one morning page entry.
Card is tied to its layout using data binding.
