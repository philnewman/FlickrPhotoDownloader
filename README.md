# Flickr Photo Downloader

This is a script that will automatically download everything from a public album, photostream, gallery, or camera roll on Flickr.

## Installation

Clone the repo from [here](https://github.com/djharten/FlickrPhotoDownloader.git).

Run ```pip install requirements.txt```

This script is written to be used with Google Chrome. You will need the Chrome WebDriver. Open Chrome and go to Menu -> Help -> About Google Chrome to find what version of Chrome you are on, then download the driver from [here](https://sites.google.com/a/chromium.org/chromedriver/downloads). Remember where you save the .exe to, you'll need to input that once when you run the program.

## Usage

Run ```python driver.py``` and follow the prompts. You will need to enter the URL for the Flickr album you wish to download(include "https://' and do not include the "pageX" along with it), the number of pages in the album(scroll to the bottom of the Flickr album to see how many), and the location of the Chrome WebDriver. Once you input all that data the images will begin to save to the directory that you have this script located in!


## Contributing
Pull requests are welcome. This was a personal project I used to learn a little more about writing scripts in Python.

## License
[MIT](https://choosealicense.com/licenses/mit/)