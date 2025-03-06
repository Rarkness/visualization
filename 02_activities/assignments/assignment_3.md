# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice. 





- For each visualization, describe and justify: 



    > What software did you use to create your data visualization?

    Python

    > Who is your intended audience?

    Beer Drinker and/or customers
    
    > What information or message are you trying to convey with your visualization?

    The types of beer made by manufacturer or Microbrewer, the name of the beer company and the number of brands they carry

    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    
    The line chart applies substantive accuracy with clear axis labels and correct data scaling, perceptual clarity using distinct colors (blue for names, orange for brands) and markers (circles, squares) for differentiation, and aesthetic appeal with a well-sized figure, balanced spacing, and a labeled legend for readability and engagement.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    I ensured reproducibility by using a structured approach: consistent data processing with groupby(), standardized visualization code in Matplotlib, fixed figure size and colors for uniformity, and reusable scripts that work across datasets without modification. 

    > How did you ensure that your data visualization is accessible?  

    I ensured accessibility by using distinct colors (blue and orange) with high contrast, clear labels and legends for easy interpretation, differentiated markers (circles for names, squares for brands) to assist colorblind users, and a well-sized figure to enhance readability. 
    
    > Who are the individuals and communities who might be impacted by your visualization?

    This visualization could impact brewery owners, beer distributors, craft beer fans, and market analysts. Breweries and distributors might use it to spot trends and competition, while analysts can track how diverse different beer types are. 

    > How did you choose which features of your chosen dataset to include or exclude from your visualization?

    I picked the Type, Name, and Brand columns because they really show how different beer categories compare. I left out other details, like specific beer characteristics or locations, to keep the chart simple and easy to read. The goal was to highlight the most useful info without cluttering things up.
    
    > What ‘underwater labour’ contributed to your final data visualization product?

    There was a lot of behind-the-scenes work to make the final chart look simple and clear. I had to clean up the data, count and group everything properly, pick the right chart, and tweak the colors and labels so it actually made sense. Plus, there was some trial and error to fix formatting issues and make sure everything looked good.







    > What software did you use to create your data visualization?
    
    Excel

    > Who is your intended audience? 
    
    Beer Drinker and/or customers
    
    > What information or message are you trying to convey with your visualization? 

    The types of beer made by manufacturer or Microbrewer, the name of the beer company and the number of brands they carry
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 

    The bar chart ensures accuracy and clarity by correctly displaying the Number of Names and Brands per beer type with clear labels. Distinct colors, logical sorting, and a labeled legend enhance readability, making comparisons easy. Balanced spacing, readable fonts, and contrasting colors improve visibility, ensuring the chart is both functional and visually engaging. 

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    I kept the data processing consistent, using clear grouping for counts, fixed color mapping for consistency, and standardized chart settings for easy replication. Anyone with the same dataset and code can recreate the visualization without issues.

    > How did you ensure that your data visualization is accessible?  

    I used high-contrast colors for differentiation, clear labels and legends for easy understanding, and ensured that the chart is readable with proper spacing. The bar format also makes it easy to interpret at a glance, even for those with visual impairments.

    > Who are the individuals and communities who might be impacted by your visualization?  

    This chart could be useful for brewery owners, beer distributors, market analysts, and craft beer enthusiasts. It helps businesses understand brand diversity, while analysts can track industry trends.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 

    I focused on Beer Type, Number of Names, and Number of Brands because they provide the most meaningful insights into brand diversity. Any extra details that weren’t necessary for this specific comparison were left out to keep the chart clean and easy to read.
    
    > What ‘underwater labour’ contributed to your final data visualization product?

    Lots of cleaning of the data, picking the right chart, adjusting labels, and fine-tuning colors to make it clear and readable






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
* Submission Due Date: `23:59 - 09/03/2025`
* The branch name for your repo should be: `assignment-4`
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
