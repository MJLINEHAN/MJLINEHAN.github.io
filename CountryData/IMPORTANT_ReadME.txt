Each country folder contains two documents. The 'country'_Popup.htm and the 'country'_Page.html. Both of these files (and by extension, the graphics on the webpage) are editable without any html, css or JS experience. 


UPDATING POPUPS
To update the text appearing in the popup window for a country, right click on the 'country'_Popup.htm file in the countries respective folder, for example Canada_Popup.htm. When right clicking the file, select open with> Microsoft excel. The file can now be styled however you see fit, including adding links, changing font/ text size, updating statistics, bold/ italic, background color (careful changing colors though it will look strange), resizing cells etc..
Saving Changes to popup Window:
1. WHEN FINISHED MAKING CHANGES, SELECT SAVE AS> WEB PAGE (HTM FILE) AND SELECT SHEET (NOT ENTIRE WORKBOOK). 
2. Once the file is saved, a final edit must be done so the links will work. Right click the file and select open with>(any text editor e.g notepad, notepad++, textedit, textmate etc..). 
3. The HTML script will appear, directly under where it says <head> (should be around line 7) copy in the following on its own line: <base target ="_parent">
4. Be careful not to delete any existing script in the htm file, If you do - repeat from step 1, and it will overwrite anyways, no worries :)



UPDATING FULL COUNTRY PAGES
To update the page that appears when selecting country - full page in a country's popup on the interactive map, go to the 'country_Page.html, for example, Canada_Page.html. 
1. Right click this and select open with Microsoft Word
2. Make whatever edits will look good (bear in mind they may display slightly different in the browser and depending on browser size, so likely best to stick to text, links and graphics on their own line.. avoid putting multiple pictures on a line with text or with each other)
3. select file> save as> Web Pag (html)
4. There is no need to even look at the html for this one :)
