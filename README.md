# The MiSTer Manuals DB - 3DO

This is a database for the MiSTer project that downloads the English manuals in .pdf form for the 3DO to the docs folder, which can be loaded from the OSD within th core by selecting "Help".

To use it simply copy and paste the below to the bottom of your downloader.ini file (found at: /media/fat/downloader.ini )

```ini
[ajgowans/manualsdb-3do]
db_url = https://raw.githubusercontent.com/ajgowans/manualsdb-3do/db/db.json.zip
```
