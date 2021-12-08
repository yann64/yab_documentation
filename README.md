# yab_Documentation

Documentation for the yab programming language.

## Adding a new language

* First thing is to copy/paste one of the already available translation in the /Help folder and change its name. As an example, you can copy/paste Help_EN to Help_PT if you want to translate the english translation to Portuguese. Every sigle file within the subfolders will have to be translated.
* You will then have to create the language data file ine the /data folder. Again, copy/paste the file from an existing language translated language you are familiar with and start from there.
* Finally, you will need to create a catalog file in the /language folder. It is used to translate the yab_Documentation gui in the desired language. To translate the French catalif file to Italian, copy the fr.catalog to an it.catalog and translate the fnewly created file to italian.