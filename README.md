# reddit-scrapper

This is a Python 3 script for downloading images from a list of user-defined subreddits up to a user-defined limit. Configuration can be found in the Configuration block near the top of the file.

One Python package is requiered to run this script, `wget`. It can be installed via pip with the following command:

* `pip install wget`

To-Do List:

* [ ] Clean-up .tmp files from broken downloads
* [ ] Check if image already exists to prevent duplicate downloads
* [ ] Fix download of non-direct image likes (ie. imgur galleries)
* [ ] Add support for more image types, files, et cetera (ie. wikipedia, all gifs)
