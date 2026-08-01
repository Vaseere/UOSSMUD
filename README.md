# Unofficial Squaresoft MUD Community Map Pack
This pack is designed to work with Mudlet only.

This is an update to the Unofficial Squaresoft MUD Community Map Pack V1.1 created by Velzard.

Contact Rynn in game, or create an issue for any areas found missing, or exits that are broken.

## Instructions
Run the following command:

lua installPackage([[https://github.com/Vaseere/UOSSMUD/blob/0f10ff8676733820f38c1df87f50e8685260c18a/UOSSMUD%20-%20CMP.mpackage]])

Once installed, use update map to download the map.

### Additional Commands
* <mark>uoss update</mark>
  - Removes the current version and downloads the latest version
<br></br>
* <mark>findme</mark>
  - Attempts to locate you on the map if you ever end up not where you should be.
<br></br>
* <mark>whereami</mark>
  - Show the name and id of your current room.
<br></br>
* <mark>uoss sw</mark>
* <mark>uoss speedwalk</mark>
  - Show a list of current available speedwalks
<br></br>
* <mark>uoss add <roomid> <speedwalkname></mark>
  - Add a new speedwalk to the room id. Speedwalk name should avoid long or complicated names that may not be supported by tables.
<br></br>
* <mark>uoss remove/rem/rm/r <speedwalkname></mark>
* <mark>uoss delete/del/d <speedwalkname></mark>
  - Remove the specified speedwalk
<br></br>
* <mark>gt #</mark>
  - Will attempt to run you to the room number
<br></br>
* <mark>gt <name></mark>
  - Has some predefined locations such as 'auction' and 'coli' that will run you to the respective rooms - more can be added in the Alias if wanted
<br></br>
* <mark>uoss p/path <roomnumber></mark>
  - Copy and display the path from your current room to the requested room to your clipboard
