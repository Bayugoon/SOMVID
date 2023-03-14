# SOMVID
Standardized Ordered Minecraft Version Identifiers

SOMVIDs are used to uniquely identify and compare two versions.
Each version id is in the style of JE-XXX-YYY-Z
XXX is three hexadecimal digits that represents the major release for that version, this part is important because there has been multiple occasions where a minor release had to be made for a previous release to hotfix a bug.
YYY is three hexadecimal digits that represents the order in which the versions where released ie. the first snapshot would be 001, the second 002, and so on.
Z is one hexadecimal digit that serves as a spot to insert new versions in between two established version ids if a new reupload of a legacy version is found.

This idea is based upon bluecrab2's original SAMVID system (https://docs.google.com/spreadsheets/d/1Y8XJN0CTCP6aQpEdq47xVLvMceZgCKmpsbemjdN7H5M/edit#gid=0) but has been more optomized for decreasing the chance of running out of ids for a major version and running out of major version ids while still keeping the indvidual ids fairly easily to memorize.

For an example on how to use ids in a program to compare versions check out this demo:
* https://bayugoon.github.io/somvid/
* https://github.com/Bayugoon/Bayugoon.github.io/blob/main/somvid/script.js
