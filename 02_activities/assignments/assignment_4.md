# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  

Note: The selected Data set is - ServiceOntario wait times (in-person)(https://data.ontario.ca/dataset/serviceontario-wait-times-in-person) which is selected from [Ontario’s Open Data Catalogue](https://data.ontario.ca/). All the required documents including python code, excel files are added in folder 'Assignment-4 documents' 

<<<<<<< HEAD
- For each visualization, describe and justify: 

1st Visualization

=======
- For each visualization, describe and justify:
  
>>>>>>> dceb3094b64a38e1a916b4d1f18d60f926d4d18b
    > What software did you use to create your data visualization?
    The data visualization is created using python's Matplotlib library to create the bar plot visualization. 

    > Who is your intended audience? 
    The intended audience are:
    Policy Makers and Administrators: To assess the performance of publicly and privately operated Service Ontario centers.
    General Public: To increase awareness of wait times and service efficiency.
    Data Analysts: To showcase insights from the dataset for improvements
    
    > What information or message are you trying to convey with your visualization? 
    The visualization aims to convey:
    A comparison of yearly average wait times (percentage of customers who waited less than 20 minutes) between publicly and privately operated Service Ontario centers.
    Key Insight: Whether public or private centers consistently perform better in terms of shorter wait times.
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    Substantive Principles: Focused on presenting accurate, summarized data (yearly averages), and also ensured that all relevant data was included without overwhelming the audience with raw values.
    Perceptual Principles: Used distinct colors to differentiate the two types of centers clearly, Added data labels to the top of the bars to aid quick comprehension.
    Aesthetic Principles: Balanced the plot by giving equal visual weight to public and private data and also used a clean layout with a descriptive title and axis labels for clarity.

    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Reproducibility in Python: I ensured all steps were performed programmatically in Python, from cleaning the dataset to generating the plot. Dependencies, like Matplotlib and Pandas, were documented in the environment file for reproducibility.
    Excel Export: I exported the cleaned dataset to an Excel file with clear sheet names, enabling easy reproduction of the visualizations using Excel or other tools.
    Impact of Non-Reproducibility:If the visualization tool were non-reproducible, it would reduce trust in the results and limit opportunities for others to verify or build upon the analysis.
    
    > How did you ensure that your data visualization is accessible?  
    Used readable fonts and a clear title to ensure the plot is understandable. Applied color coding with distinguishable colors and added data labels to the bars.
    
    > Who are the individuals and communities who might be impacted by your visualization? 
    Service Ontario Staff: Insights from this visualization might highlight areas for operational improvement.
    General Public: Increased transparency might help customers decide which type of center to visit for shorter wait times. 
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    Included:
    Yearly Average Wait Times, to give a high-level summary and make the data comparable across time and added Public and Private Center Data together for a side-by-side comparison
    Excluded:
    Detailed monthly data to avoid cluttering the visualization and overwhelming the audience.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    The "underwater labour" included:
    Data Cleaning: Filled the missing records with the means value of the centre and also Aggregated monthly data into yearly averages for simplification.
    Preprocessing: data validated seprately as public and private datasets.
    Coding: Written Python scripts for data analysis and visualization. Debugging and refining the visualization code.
    Testing: Ensuring the visualization was legible and effective across different screen sizes and resolutions.
    Exporting Data: Creating a user-friendly Excel file to facilitate additional analysis in alternative tools.


2nd Visualization

    > What software did you use to create your data visualization?
    I used Microsoft Excel to create the visualization

    > Who is your intended audience? 
     The intended audience includes decision-makers, managers, and stakeholders in ServiceOntario or similar organizations, as well as researchers or analysts interested in service efficiency trends
    
    > What information or message are you trying to convey with your visualization? 
    The visualization conveys the proportional distribution of waiting times (less than 20 minutes) for public vs. private ServiceOntario centers month by month. 
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    Substantive Principles: The data is aggregated and presented month-wise to give meaningful comparisons. Applied by summarizing the dataset to show proportions for each month for public and private centers.
    Perceptual Principles: The use of a 100% stacked column chart ensures that the proportions (relative performance) are visually clear and easy to compare. Applied by ensuring distinct colors represent public and private centers across different years.
    Aesthetic Principles: The colors are consistent, and the axis titles and labels are descriptive.

    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    The visualization is reproducible because, the cleaned dataset was exported from Python and organized systematically in Excel. Steps to create the chart are well-documented in different sheets. If reproducibility were an issue, stakeholders would face challenges validating or updating the analysis, which could reduce its credibility.
    
    > How did you ensure that your data visualization is accessible?  
    The chart uses descriptive titles and axis labels for clarity. Also a legend is provided for easy interpretation of colors.
    
    > Who are the individuals and communities who might be impacted by your visualization? 
    ServiceOntario management: They can use the insights to improve resource allocation and service efficiency.
    Customers: Understanding which months or centers perform better could lead to improved service experiences.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    Included Features: Monthly proportions for both public and private centers from multiple years.
    Excluded Features: Absolute values (like total waiting time or centre counts) were excluded since the focus is on proportional comparisons.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    The "underwater labour" included:
    Data Preparation: Cleaning and organizing the data in Python, then exporting it to Excel.
    Combining Data: Merging public and private datasets into a single sheet for ease of analysis.
    Chart Customization: Adjusting axis labels, titles, and formatting for better readability.

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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
