# MyBB_Theme_Cerulean

Cerulean v1.3
» About:

This is a simple dark theme for MyBB enthusiasts styled similar to the ACP Style of the same name.

Cerulean v1.3
» Installation:

1.) After downloading the Theme unpack it (with 7-Zip for example)
2.) Upload the contents of "Upload" into your forums main directory.
3.) Go to the Admin Control Panel under Themes > Import
4.) Search for the XML File titled "Cerulean-theme.xml" in the theme folder found on your computer and click the Button "Import Theme" this will upload the file from your computer to your forum.
5.) Now have fun with your forum!

Cerulean v1.3
» License:

You may not remove or change the MyBB copyright nor the Designed by: "Vintagedaddyo" statements in the footer of this theme's templates. You may use and modify this theme to your personal likings, but redistributing a modified version for download is prohibited, unless you have explicit written permission from "Vintagedaddyo", though you are allowed to redistribute a copy that has not been modified.

Cerulean v1.3
» Changelog:

History:

11/1/2021 — Updated "Cerulean-theme.xml" file to 1.8.29
02/08/2021 — Updated "Cerulean-theme.xml" file to Cerulean v1.3
08/10/2020 — Updated "Cerulean-theme.xml" file to 1.8.24
07/24/2020 — Updated "Cerulean-theme.xml" file to 1.8.23
06/27/2019 — Updated "Cerulean-theme.xml" file to 1.8.21
04/05/2019 — Updated "Cerulean-theme.xml" file to 1.8.20
09/11/2018 — Updated "Cerulean-theme.xml" file to 1.8.19
08/30/2018 — Updated "Cerulean-theme.xml" file to 1.8.18
03/28/2018 — Updated "Cerulean-theme.xml" file to 1.8.15
04/21/2016 — Initial Theme Creation


Read changelog:
https://community.mybb.com/mods.php?acti...og&pid=735

To Do:
* fix any minor styling issues
* complete postbit icon sections of thread status that I haven't fully completed yet


Due to the addition of css groupimage replacement, we need to after install modify for font awesome icon and add in groups in groupimage input for example for each usergroup its respective group name:

Quote:
Group Image

Here you can set a group image which will show on each post made by users in this group.

Example
<icon class="fa fa-cog"></icon><i>administrator</i>




<icon class="fa fa-gavel"></icon><i>super moderator</i>




<icon class="fa fa-gavel"></icon><i>moderator</i>




<icon class="fa fa-user"></icon><i>registered</i>


Etc, etc....
