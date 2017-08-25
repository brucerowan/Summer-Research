**Summer Research**

*June 22, 2017*

Started learning how to use Github, started looking into what projects were available,
and how the structure of Data for Democracy works.

*June 25, 2017*

Spoke with the founder of D4D, and a few other active members. This me some ideas about what projects to join. 

*July 5, 2017*

I was able to finish Data for Democracy's [Github tutorial](https://github.com/Data4Democracy/github-playground)

*July 7, 2017*

Joined group [town-council](https://github.com/Data4Democracy/town-council).
I was interested in the similarites to Cal Poly's [Digital Democracy](http://www.iatpp.calpoly.edu/projects/digitaldemocracy.asp).

I was given the task to scrape the meeting minutes/agenda of the city of Berkely. 
This project is using a powerful but complicated webscraping framework called Scrapy. I spent about 2 days trying to understand the framework after getting one of their example scrapers to work on mycomputer. 
However, when I asked the project manager for help she said I should just wait because she was coming out with some sort of visualization or tutorial to help people get the hang of scrapy. 

*July 20, 2017*

Many cities use a common content management systems(cms) to post their meeting contents. Legistar is a common cms that was used by several cities. 
One member of town council made a template that could potentially scrape any city's meeting content.
I decided to be the one to test this template on the Legistar cities. 

*July 24, 2017* 

Using some object oriented programing in python, I was able to effectively create python files that were able to call the legistar template file for six cities in the Bay area: 
Hayward, Cupertino, Mountain View, San Mateo, San Leandro, and Sunnyvale.

*July 25, 2017*

Found a task through the [Indivisible group/project](https://github.com/Data4Democracy/indivisible).
The task is to create a training dataset to classify events to actions by scraping several websites.

*July 27, 2017*

I was able to create a webscraper using the beautiful soup package for the site https://www.risestronger.org/action. 
That was able to output a csv file that held event names and their action classification.

*July 28, 2017*

I was recruited to join a project interested in visualising public opinion polls, but want to finish the previous task before I look more into this.

*Augest 1, 2017*

Have been trying for a few days to scrape https://resistancenearme.org/ but ran into trouble. Tried asking for help, but I'm still stumped.

*Augest 5, 2017*

Still working on scraping https://resistancenearme.org/ got some help but then they changed the format of the website. Just figured out how to click the items in the dropdown menue using the selenium package. This is a huge step forward and I should be able to finish scraping the website tomorrow!

*August 9, 2017*

Finished the scraper for https://resistancenearme.org/. I could still put in a little more work to seperate the date and time variables as well as implementing a function that would actually add the new csv to a larger csv from other websites. Once I do that I will see what the next steps are. The people in this project have been really slow at responding. 

The woman with the civic data viz group thought my ideas of the segmented bar charts were good. I think they are still collecting data right now.

I found another task with a project called USA Dashboard. They are trying to create a big dashboard to track important metrics in the US. This is important to see what policies should be made and the effects of those policies.
The specific task I am doing with them is doing some sort of exploratory data analysis on crime data. I have just been given access to the data I think, but I havent started yet. 

*August 13*

Still would like to add some features to the indivisible scrapers, however everyone on that project hasnt gotten back to me yet.

USA dashboard project is kicking off. They sent me to a site called Mode Analytics but there were only 4 datasets on there, so I was worried we didn't have enough data. However, I just checked the github and they scrapped a good bit of data there.
I'm currenty trying to think of ways to merge all the (crime) data together from each state and think of ways to perfrom EDA on them.

There is a cool new side project through one of the immigration channels. I'm not too sure what they are trying to do with this data, however they want to scrape social media, mainly twitter, to do some research on specific hashtags and handles. 
Using the twitter API is not going to work for this because it only allows you to scrape one week in the past. 
To get around this I need to use Docker and Scrapy. Scrapy is the webscraping library that I tried and failed using on the first task. However, I was given a tutorial to do, and from what I gathered both of these tools are extremely useful, so I thought I'd give it another go. 



*Auguest 21*

Still havent gotten word back from the indivisible scraper guys. All I need to do is figure out how to merge all the csv's together using a base_scraper class that one person has already created. Once that is done, the issue will be complete, unless any changes need to be made.

I was working on doing the USA Dashboard EDA for the crime data with someone but he hasnt been online for a week now so I think I'm just going to do this on my own.

I'm still waiting on a responce to figure out why Docker is needed to scrape twitter data. In the meantime I will be finishing up the Scrapy tutorial. 

Ryan Moore, a cal poly stats major wants to help with the EDA task, so we will work on that tomorrow most likely. 



*August 24*

Finally got ahold of the person who can help me with the indivisible scraper. He said he was really busy with work but I'm still waiting on him to actually help me.

Still waiting to get help for the twitter scraping project. I finished both the Docker and Scrapy tutorials but I still have no idea why Docker is needed to scrape twitter. 

Made some moves on the USA-Dashboard project. My task is to do some EDA on the crime data they collected. I put all the files into a google drive and created a google sheet that contains a lot of meta data (# of years, CSVs, schema of the data). Of the 17 cities I have data, I think 15 have 2016 data. Right now I'm in the process of subsetting the csv's to just the 2016 data, and then finding the most common crimes in each city and then the most common crimes accross all the cities. I'm still thinking of some more things I can do with this data. Hunter, if you are reading this, and have any ideas let me know! I can give a link to access the google drive. The data is pretty simple, just date, type of crime, and counts. 


