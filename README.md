# FreeAgentValorantWebScrapper

This script is used with a csv file with the following columns (does not need to be same names):
playerName, TwitterURL, player agent roles (ie controller, sentinel, etc), VLR link to players main page

ex of VLR link: https://www.vlr.gg/player/8480/aspas

This script will currently return the the 50 most recent matches a player has played, including the opponent,
the date, and the players rating in the match. The goal is to show a players performance over time, with the
ability to subset by only matches against a certain level of team.

In the future, their will be an option to pick only top X teams on VLR, in order to be able to subset within the script
itself, rather than manually.

Any questions please message Voxize#2307 on discord, and mention you have questions about the "Free Agent Web Scrapper"
