# Short Term Price Movement Analysis
When 5 day moving average crosses above Acceleration line, does it signal a gain in short term.

# Table of contents
1. [Installation](#Installation)
2. [Motivation](#Motivation)
3. [Repository Structure](#Structure)
4. [Results](#Results)
5. [Licensing, Authors, Acknowledgements](#Licensing)



## Installation <a name="installation"></a>
The code assumes you use Anaconda (Python 3) and no additional libraries needs to be installed.



## Motivation <a name="Motivation"></a>
As part of the activities of Udacity's Data Science Nanodegree I'm enrolled, I have chosen to use data supplied by Pan-Origins to analyze short term trends of stock price movement. I wanted to do something that could be applied in the real world, to help make an investing decision. As I have worked at a quantitative hedge fund for over 5 years, I have realized the importance and significace of ML/AI and the affect it can have on the industry, so this is my first step in it's discovery. After carefully looking at the data, here are the questions that I have proposed: 
1. When the 5 day Moving Average crosses above the Acceleration Line, after short term (5 days), will the price move up compared to the    day it crosses?
2. Which binary regression model or classification model is best fit or the problem, and gives the best accuracies in prediction?
3. Which features are relatively important and which are not?
4. What are the correlations between features, and can they be explained? 
5. To answer question 1, is the model fit to predcit price movement in future investment opportunities?



## Repository Structure <a name="Structure"></a>
- The ipyinb file is the code notebook file containing all the codes written to clean and wrangle data, to analyzing data and producing model and graphs.
- The csv file is contained in the zip folder, it is the raw file supplied by Pan-Origins LLC, containing raw data over the last three years, of their indicators. including the features and targets used in this project.
- The assets folder contains graphs and pictures generated and produced that is used in the deployment of this projet on the blog site.



## Results <a name="Results"></a>
A more detailed description of the project, its analyses and insights can be found at the post available here.



## Licensing, Authors, Acknowledgements <a name="Licensing"></a>
Must give special thanks to Pan-Origins LLC for providing the csv data, which is availble for public use. Feel free to use the code provided that you give credits / cite this repo, as well as to contribute.
Codes that were referrenced are found at : https://medium.com/@garg.mohit851/random-forest-visualization-3f76cdf6456f



