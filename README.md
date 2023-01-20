<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>
<h3 align="center"><a href='https://www.udacity.com/course/data-analyst-nanodegree--nd002'> Udacity Data Analyst Degree </a></h3>
<h4 align="center">  Project II: Investigate a Dataset </h4>
<h5 align="center">  December 2022 </h4>

## Table of Contents
- [Introduction](#Introduction)
- [Project Instruction](#instruction)
- [Project Submission](#submission)
- [Result](#result)

## Introduction <a name="Introduction"></a>

In this project, I made an analysis on global and local (Bangkok) temperature trend data and compared these trends. The process is starting from apply the SQL to extract data from the Udacity's Project database as a CSV file, the use Python for data analysis and visualization. Finally, sprinkle some magic powder to create PDF report via Canva.

## Udacity's Project Instruction <a name="instruction"></a>
For the final project, you will conduct your own data analysis and create a file to share that documents your findings. You should start by taking a look at your dataset and brainstorming what questions you could answer using it. Then you should use pandas and NumPy to answer the questions you are most interested in, and create a report sharing the answers. You will not be required to use inferential statistics or machine learning to complete this project, but you should make it clear in your communications that your findings are tentative. This project is open-ended in that we are not looking for one right answer.

<ul>
  <li><strong>Step One - Choose Your Data Set</strong><br>
Click this  <a href="https://s3.amazonaws.com/video.udacity-data.com/topher/2018/July/5b57919a_data-set-options/data-set-options.pdf"> link </a> (available in a Google doc <a href ="https://docs.google.com/document/d/e/2PACX-1vTlVmknRRnfy_4eTrjw5hYGaiQim5ctr9naaRd4V9du2B5bxpd8FEH3KtDgp8qVekw7Cj1GLk1IXdZi/pub"> here </a>) to open a document with links and information about data sets that you can investigate for this project. You must choose one of these datasets to complete the project.</li>
       <br>
  <li><strong>Step Two - Get Organized </strong><br>   
Eventually you’ll want to submit your project (and share it with friends, family, and employers). Get organized before you begin. We recommend creating a single folder that will eventually contain:</li>
  <ul>
        <li>The <strong> report </strong> communicating your findings</li>
        <li> Any<strong> Python code </strong>you wrote as part of your analysis</li>
        <li>The <strong>data set </strong>you used (which you will not need to submit)</li> 
   </ul> 
  <br>
  You may wish to use a Jupyter notebook, in which case you can submit both the code you wrote and the report of your findings in the same document. Otherwise, you will need to submit your report and code separately. If you would like a notebook template to help organize your investigation, you can click here. Or there may be a page in the project here called Project Workspace: Complete and Submit Project, where you can do all your work and submit the project.
  <br><br>
  <li><strong>Step Three - Analyze Your Data</strong><br>
Brainstorm some questions you could answer using the data set you chose, then start answering those questions. You can find some questions in the data set options to help you get started.

Try and suggest questions that promote looking at relationships between multiple variables. You should aim to analyze at least one dependent variable and three independent variables in your investigation. Make sure you use NumPy and pandas where they are appropriate!
  </li>
  <li><strong>Step Four - Share Your Findings</strong><br> 
<br<br>Once you have finished analyzing the data, create a report that shares the findings you found most interesting. If you use a Jupyter notebook, share your findings alongside the code you used to perform the analysis. Make sure that your report text is contained in Markdown cells to clearly distinguish your comments and findings from your code work. You should also feel free to use other tools and software to craft your final report, but make sure that you can submit your report as an HTML or PDF file so that it can be opened easily.
  </li>
 <br> <li><strong>Step Five - Review </strong><br> 
Use the Project Rubric to review your project. If you are happy with your submission, then you're ready to submit your project. If you see room for improvement, keep working to improve your project!
  </li>
   </ul>
</ul>
  


## Project Submission <a name ='submission'></a>
What to include in your submission:


 <ul> <li>A PDF or HTML file containing your analysis. This file should include:</li>
   <ul>
   <li>A note specifying which dataset you analyzed
   <li>A statement of the question(s) you posed
   <li>A description of what you did to investigate those questions
   <li>Documentation of any data wrangling you did
   <li>Summary statistics and plots communicating your final results    
   </ul>
  <li>Code you used to perform your analysis. If you used a Jupyter notebook, you can submit your .ipynb. Otherwise, you should submit the code separately in .py file(s). </li>
  <li>A list of Web sites, books, forums, blog posts, github repositories, etc. that you referred to or used in creating your submission (add N/A if you did not use any such resources). </li>
</ul>  

## Result <a name="result"></a>
<p align="center">

From the investigation, I found that most of the movies in the data set has a low rating. However, the high rating movie uses less budget in average than moderately low and medium rating movie but have the longest runtime on average among the group. 

For the characteristic of high rating movie, it invested a budget (adj) in average of around \$ 46,617,355 and got an average revenue (adj) of around $ 234,511,369. On average, the high rating movie has 119 minutes of runtime and got voting at 7.18.

It's also very interesting that the word 'one' and 'story' have the highest occurrence in the tagline of high rating movie at 73 times.

The application of this analysis can be used to plan for movie production such as budget spending or runtime duration, to get the high rating movie. Additionally, the last research question about the tagline can help the marketing (copywriting team) to design communication messages (word) for the movie promotion.

**Limitation**: This analysis has some limitations which are:

1. The dataset doesn't define the unit of measurement of runtime (the minute is the researcher's own implication)
2. The range vount_count is pretty wide as the minimum is 10 and the maximum is 9767. Thus the reliability of the vote should be taken into consideration
3. Even though the data just show the maximum of vote_average is 8.4, the data doesn't confirm the maximum and minimum in scale value that the voter can vote. Thus we can't officially say the maximum vote_average is 8.4 out of 10.

</p>
