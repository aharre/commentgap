# The News Comment Gap and Algorithmic Agenda Setting in Online Forums
Project repository

* 01_Code: used for scraping derstandard.at with RSelenium
* 02_Code: used for data cleaning, and analysis of comment preferences for readers/journalists
* 03_Code: used for analysing ranking algorithms
* 04_Code: used for beta regression model for FORUM score
* 05_Code: used for creating figures and tables for the article

### The News Comment Gap and Algorithmic Agenda Setting in Online Forums
#### Flora Böwing, Patrick Gildersleve

_The disparity between news stories valued by journalists and those preferred by readers, known as the "News Gap", is well-documented. However, the difference in expectations regarding news related user-generated content is less studied. Comment sections, hosted by news websites, are popular venues for reader engagement, yet still subject to editorial decisions. It is thus important to understand journalist vs reader comment preferences and how these are served by various comment ranking algorithms that represent discussions differently. We analyse 1.2 million comments from Austrian newspaper Der Standard to understand the "News Comment Gap" and the effects of different ranking algorithms. We find that journalists prefer positive, timely, complex, direct responses, while readers favour comments similar to article content from elite authors. We introduce the versatile Feature-Oriented Ranking Utility Metric (FORUM) to assess the impact of different ranking algorithms and find dramatic differences in how they prioritise the display of comments by sentiment, topical relevance, lexical diversity, and readability. Journalists can exert substantial influence over the discourse through both curatorial and algorithmic means. Understanding these choices' implications is vital in fostering engaging and civil discussions while aligning with journalistic objectives, especially given the increasing legal scrutiny and societal importance of online discourse._

Read the [preprint on arXiv](https://arxiv.org/abs/2408.07052)

You can try out our FORUM score for evaluating ranking algorithm performance using this repo: [PyFORUM](https://github.com/pgilders/pyforum)
