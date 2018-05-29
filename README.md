# galactic-map
This HTML file contains d3.js work to create a galactic map from the data files from eddb.io/api for Elite Dangerous

It has a couple of dependencies:
1. D3.js - included by script src tag
2. d3-polygon - included by script src tag
3. d3-queue - included by script src tag
4. d3.geom.concaveHull.js -- included direct. Download this separately from Github. Google the file name if necessary

The data this operates on are the factions.json and systems_populated.json files that are available for download from eddb.io/api. Simply drop them in the same location as this HTML file.

This map also include the "standard" Alliance logo, AllianceInsignia.png. You can find this easily on the web.

----

For those new to D3.js/web development... One of the easiest ways to get started is to download Brackets. This has a preview built in that ties into Chrome, and you can use the Dev Tools in Chrome. It's a light text editor that is perfect for tasks like this. If your IDE/dev env of your choice has web preview, by all means use that.

