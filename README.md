# Kodi-Videofile-renamer
Three tools quickly thrown together by me. It helps to quickly rename Videofiles for Kodi manuelly. With this naming scheme Kodi can fetch Video data quite easally.
It just adds [S0x Exx] in front oj your existing filename.
Please note that I created this only for my personal use because I didn't find any Programm like this on the internet. I know this is just quick and dirty but works.

1. Copy and Past CreatList.bat and rename.bat to the folder where you have your files for renaming.
2. Execute CreatList.bat it will creat Namensliste.txt with every file in this directory.
3. Open Namensliste.txt
4. Open the Serien Rename Tabelle.xlsx
5. Copy your filenames from Namensliste.txt in the right order to Serien Rename Tabelle.xlsx
6. The first filename should be EP01 copy it to A2 in Serien Rename Tabelle.xlsx
7. Continue with the rest of the EPs
8. In the column "Staffel" can you change your Season Number, in the column "Episode" can you change your EP Number.
9. In the column "Episoden mit Kodinamen" are your finished names.
10. Is everything Ok you can copy the finished EPs + code from the column "Fertiger Rename Code".
11. Clear the Namensliste.txt and past this fresh code in it.
12. Execute now rename.bat and everything is finisched now.
