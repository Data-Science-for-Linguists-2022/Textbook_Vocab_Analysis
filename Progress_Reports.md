# Progress Report 3
Great News Everyone! I finially figured out how to get my data into a workable object.

I've included my progress with (rough-ish) data frames that have the Russian entry (with annoying additional info sometimes), the English definintion for that entry, and then the level of the textbook in came from.

For my final submission my goals are as follows:

1. Define a function to return part of speech for a Russian entry into a new POS column based on regex formulae
  - This will cause some challenges. I will look for morphological lists to supplement my knowledge and try to figure out a way to make this workable
  - I am not above doing this by hand. It might honestly be faster
2. Once I accomplish this I can get some concrete statistics going
  - i.e. trying to find overlap in terms based on level, percentages of POS based on level and so on

Ultimately, I'm excited about and enjoy this project but have found that due to the way that I can access the data (pdfs and having to rely on less than accurate copy and paste measures to get it into plain text form) this was a considerable undertaking. The Data, although attempting to keep some form of consistency across levels, makes it a challenge to work with using computational methods especially with regex. I might ask for more of your feedback on how I might separate the additional case, usage, and collocative information information apart from the focused items.

# Progress Report 2
I was able to save the portions of the pdfs that I need as plain text files.

I start to explore these files in [Data_Exploration.ipynb](https://github.com/Data-Science-for-Linguists-2022/Textbook_Vocab_Analysis/blob/main/Data_Exploration.ipynb) but for some reason
github is not rendering the output that I see. If anyone can tell me what I'm doing wrong, I would greatly appreciate it. Does it only render output for pandas dataframes?

Another couple annoying roadblocks regard the vocab forms and format of the partial Russian frequency dictionary I downloaded through [Sketch Engine](https://www.sketchengine.eu/russian-word-list/). I found out that the list is entirely inflected forms (I opened the csv file in notepad) this will likely be a problem because the textbooks give the targeted vocab in dictionary forms (masculine singular adjectives, infinitive verbs, etc.)

The csv file reads in with an error when trying to use pandas, so I'm not sure how to proceed and I'm just getting really discouraged, but I feel like I've sunk too much time to pivot with only really a month left. So I'm just going to do my best :/

# Progress Report 1
I know that I should have more to show for this progress report, but I'm still figuring out how to use pdf text extractor libraries on Cyrillic text.

So far, I have gotten access to electronic versions of two of the textbooks in the series that I'm using and I'm very nearly done digitizing the last.

I've included the beginning of the jupyter notebook that I'm making for the project that shows how I'm fiddling around with libraries like PyPDF2 and pdfminer. Like I said, I still need to take some time to figure out how to use them with Cyrillic and I want to see what form the data gets output as.

I'll definitely have more to show and better results at the next check-in.

I've also downloaded a subset of the Russian National corpus, but I found another corpus of that is twice the size as of the RNC at 2 million words. There is one that's even larger that uses livejournal, facebook, twitter, and vkontakte texts but I wonder whether that will be as representative of the language like the RNC...

Food for thought as I continue
