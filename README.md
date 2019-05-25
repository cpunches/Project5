## Exploring PISA 2012 data 
## by Corey Punches


## Dataset

The dataset used was the PISA data from a 2012 study on students from 65 economies around the world. Student scores in math, reading, and science were captured as well as a multitude of answers about the students perception of their ability, anxiety they feel, etc.

There are 485,490 rows of student data with which originally had 636 columns. Through cleaning I pared the data down to the 10 columns of interest. There are 7 columns of qualitative categorical data which have been made into ordered factor variables of multiple levels.


### Features in the dataset to help support investigation into feature(s) of interest

Math score, gender, and the features:
- ma_get_tense                   
>Math anxiety - math makes student feel tense
- ma_get_nervous                 
>Math anxiety - math makes student feel nervous
- ma_feel_helpless               
>Math anxiety - math makes student feel helpless
- ma_worry_about_poor_grades     
>Math anxiety - student worries about making good grades
- msc_worry_not_good_at          
>Math anxiety - student worries they are not good at math
- ma_worry_that_difficult        
>Math anxiety - student worries that math is too difficult for them

will be the most important in finding answers to my questions. *note that I have included msc_worry_not_good as an anxiety measure as it seemed applicable*

## Summary of Findings
 Proportions of responses seem reasonable as the strong aggreements and strong disagreements have the lowest proportion except when asking about worrying about bad grades, there seems to be a lot of strong agreement in terms of worrying about getting good grades in math.

 Students self identifying they do or do not enjoy math does seem to be reflected in the test scores - students claiming to not enjoy math have score less than the students who claim to enjoy math.

 There seems to be a clear indication that females identify as having more feelings of anxiety around math than males.

 It seems clear that there is indeed a correlation between a student's feelings of anxiety about math and their test scores. Those students reporting the most anxiety had the lowest test scores, regardless of gender. 

 It seems surprising that there are slightly more males giving affirmation to feelings of anxiety than females, but not by much. It is also surprising that the male students that reported the least amount of anxiety, had higher scores than females who also reported the least amount of anxiety. The reasons for this are not clear and are beyond the scope of this report although I suspect cultural biases where males are more directed towards math and science than females to be part of the reason.


## Key Insights for Presentation

It seems that a student's feelings of anxiety and self-doubt in their mathmatical ability does correlate to test scores achieved. Males are slightly more more positve about their math ability and lessened anxiety and do have slightly higher scores than their female classmates. It's beyond the scope of this investigation but cultural biases probably play a part in males feeling better about themselves in relation to math.

## Resources

<ul>
    <li><a href="https://stackoverflow.com">StackOverflow</a></li>
    <li><a href="https://pandas.pydata.org/pandas-docs/stable/reference/frame.html#">Pandas Dataframe reference</a></li>
    <li><a href="https://knowledge.udacity.com/?nanodegree=5d1a8326-496f-11e8-b51d-0b52a2c1b841&project=56f678d8-496f-11e8-b3a8-5b814806136d">Udacity Knowledge</a></li>
    <li><a href="https://www.apress.com/us/book/9781484239124">Python Data Analytics</a></li>
    <li><a href="https://www.barnesandnoble.com/w/data-wrangling-with-python-jacqueline-kazil/1126350836?ean=9781491948811">Data Wrangling with Python</a></li>
    <li><a href="https://www.amazon.com/gp/product/1491952962/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1">Practical Statistics for Data Scientists</a></li>
    <li><a href="https://www.amazon.com/Python-Data-Analysis-Wrangling-IPython-ebook/dp/B075X4LT6K/ref=sr_1_fkmr0_1?keywords=O%27Reilley+Python+Data+Wrangling&qid=1554835853&s=gateway&sr=8-1-fkmr0">Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython 2nd Edition</a></li>
    <li><a href="https://www.amazon.com/Pandas-Cookbook-Scientific-Computing-Visualization-ebook/dp/B06W2LXLQK/ref=sr_1_3?keywords=pandas+cookbook&qid=1558657434&s=gateway&sr=8-3">Pandas Cookbook</a></li>
</ul>
