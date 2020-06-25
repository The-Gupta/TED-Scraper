# TED-Scraper
Web Scraping of TED.com for complete Metadata, Transcript, Audio, Video, Images using Parallel Programming.

Environment: Google Colab with Google Drive without any Hardware Accelerator. Python: 3.6.9

[Scraped Data](https://www.kaggle.com/thegupta/ted-talk)


### Context

I was looking for an interesting dataset for a personal Data Science project, and I'm a fan of TED. So, I looked for the TED dataset, found [Rounka's](https://www.kaggle.com/rounakbanik/ted-talks) but it is incomplete and outdated. Then, [I scraped myself](https://github.com/The-Gupta/TED-Scraper/blob/master/Scraper.ipynb) and made it super fast using Parallel Programming. Now, it **downloads all Metadata along with the Transcript in 300 seconds of all 4609 Talks on the website***. This is the **most comprehensive TED Talk dataset** which includes [media files](https://drive.google.com/drive/folders/1clqw9izazxafPDuIekXQYYdI-J42VvCR) (images, audio, and video) too!

*Scraped on 24-JUN-20. One can scrape entire TED.com using the code to get the latest dataset in 5 minutes.

Downloading media files take less than 2 hours in total - 2 minutes for photos of Speaker and Talk, 10 minutes for Audio, 1.5 hours for videos. <br> TED_Talk.xlsx and TED_Talk.csv contain Metadata and Transcript. Folder Names are intuitive. All media files are named by _talk__id_, except in PHOTO__SPEAKER files are named by _speaker__id_ of the primary Speaker.

**The code shows a way to scrape at scale.** 
