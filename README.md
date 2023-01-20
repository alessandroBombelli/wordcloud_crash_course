# wordcloud_crash_course

I have always found wordclouds quite amazing tools for visualization and dissemination. There are several available online tools to geenrate wordclouds (see for example https://www.wordclouds.com/). While these tools work generally fine, I wanted to be able to come up with a more tailored and customizable way of producing a wordcloud. In this short tutorial, I will show a Python procedure based on the ```wordcloud``` package. Of course, I am still experiencing some limitations in the final product, and hence suggestions for improvement are highly appreciated (in case, feel free to reach out to me at a.bombelli@tudelft.nl).

To have a meaningful wordcloud, we wil ldo the following:

* From Scopus, we have downloaded a list of academic papers (journal papers, conference papers, books) satisfying the following conditions in the abstract, title, or keywords: (TITLE-ABS-KEY(( "air transport"  OR  aviation  OR  airports  OR  airlines )  AND  (sustainability OR sustainable)). In princple, we are interested in papers dealing with sustainability in aviation
* We will use all the words in the abstracts of such academic papers to generate out set of words (with some filtering)
* We will use such set to generate our wordcloud. Since we are dealing with aviation, we will be generating our wordcloud in the shape of an aircraft
* As an extra, we will also use some extra information retrieved from Scopus to analyze some trends in the academic literature pertaining sustainability in aviation

This is the final outcome we want to achieve:

![wordcloud](https://github.com/alessandroBombelli/wordcloud_crash_course/blob/main/wordcloud.png)

https://github.com/alessandroBombelli/wordcloud_crash_course/blob/main/wordcloud.png
