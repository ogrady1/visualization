# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 

my data: https://open.toronto.ca/dataset/neighbourhood-crime-rates/
(included .csv in branch assignment folder)

- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice. 

- python: 
'../../02_activities/assignments/python_crime_visualization_A3.ipynb' 
'../../02_activities/assignments/scaled_total_shootings_plot.png'
- tableau:  
https://public.tableau.com/app/profile/ryan.o.grady/viz/TorontoCrimeRateByNeighbourhood/Sheet1
'../../02_activities/assignments/Tableau_Visualization.png'


- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?

- python (using matplotlib, pandas, os, sklearn) 
- Tableau public


    > Who is your intended audience? 
- python: This is a very simple plot that could be used by police, policymakers, journalists, or anyone who has an interest in investigating a corelation between the total number of shootings in a year vs. the total number of crimes. 
- tableau: This is a comparison chart that could be used by someone who is worried about crime when choosing a place to live. It is interractive so different neighborhoods can be compared and a simple all encompassing "total crime rate" field has been calculated to conviniently compare.

    > What information or message are you trying to convey with your visualization? 
- python: There is no distinct corelation between the number of crimes in a year and the number of shootings.
- tableau: Relative to other neighborhoods, which areas in toronto have more or less criminal activity. Are there trends within neighborhoods, for example is a historically dangerous area becoming more safe over time. 

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
- python: I made a basic plot with two lines. I added labels, titles, and a legend. It was important to use a scaler to properly visualize drastically different numbers.
- tableau: It was my first time using tableau, so i went with my instinct and tried to find a way to represent the data in a meaningful way. I ended up with side-by-side bar graphs with a title, labels and tooltips.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
- python: I saved the data as csv and used a relative path for the data so it can easily be replaced or even built into a pipeline for updating. 
- tableau: The data was downloaded and then imported to tableau in a csv format, and the results were published to the public. The onyl change made was a calculated field within tableau.

    > How did you ensure that your data visualization is accessible?  
- python: i used plt.style.use('tableau-colorblind10') although i don't think it did much - at least it's  high contrast. I kept it very simple and easily digestible, no images. I could have included alt text or annotations to go farther. plain typefaces.
- tableau: i used the color blind color palette. The tooltips are helpful. It's publicly available on tableau's site which likely has alt text. plain typefaces.

    > Who are the individuals and communities who might be impacted by your visualization?  
- python: This plot is an oversimplification of the issue. Some areas/communities in Toronto tell different stories than the overall 'total' data that i considered. If used to influence policy or even in journalism this could be biased. 
- tableau: real estate agent/home sellers/landlords might be impacted by this transparency if buyers are sensitive to crime. 

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
- python: I picked features that would be meaningful when visualized side by side - gun violence vs. total crime.
- tableau: I worked with the total crime to give a broad overview of the issue.

    > What ‘underwater labour’ contributed to your final data visualization product?
- python: the DSI staff for setting up all my python tools and environments and course material, the toronto police for gathering this data, etc.
- tableau: The tableau developpers for keeping my visualization online and accessible.

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 13/07/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
