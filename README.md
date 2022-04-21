# webscrawler_hacker
Using the language that you feel most proficient in, you’ll have to create a web crawler using scraping techniques to extract the first 30 entries from https://news.ycombinator.com/ . You’ll only care about the title, the number of the order, the number of comments, and points for each entry.


From there, we want it to be able to perform a couple of filtering operations:
- Filter all previous entries with more than five words in the title ordered by the number of comments first.
- Filter all previous entries with less than or equal to five words in the title ordered by points.

**the necesary libraries must by installed in python by using pip,**

**first try on cmd**

        py -m pip --version

now once pip is installed try:

        py -m pip install numpy

and

        py -m pip install scrapy

once the two libraries have been installed
enter the location of the folder where the file has been installed

        cd "the folder locarion" or cd and drag the folder to the cd

once press enter and type

        py -m scrapy runspider webcrawler_hacker.py
        
in comparison with web that it look like this:

![image](https://user-images.githubusercontent.com/77937750/164562126-c6f6bc5c-c77e-4801-ba26-8cef6d634f6b.png)

once the program finish running it look like this:

![image](https://user-images.githubusercontent.com/77937750/164562357-16869f95-7e38-451c-af4a-5c68955ee706.png)

![image](https://user-images.githubusercontent.com/77937750/164562400-ec87d35f-58c0-4791-8caf-35d0eed2c832.png)

![image](https://user-images.githubusercontent.com/77937750/164562468-eca19ebb-2f07-4044-bf77-7018b9a0a332.png)
