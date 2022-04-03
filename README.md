# Scrapping Images from Unsplash #
- Using regex (to identify the relevant keyword) and selenium (to retrieve the download links found in HTML page source)
- Headed browser is used for automation as certain website blocks headless browser, although more elegant alternatives are very likely to exist 
 
The overall procedure goes:
1) Reformat and add the query (search term) into URL, additional flag can be added to increase relevancy
2) Browse the URL
3) Parse the html page source and retrieve the relevant download links found
4) Download the images correspond to the links
