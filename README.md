## Web Design Homework - Web Visualization Dashboard (Latitude)

## Table of contents
* [Homework_Assignment_Background](##Homework_Assignment_Background)
* [Project_Task](##Project_Task)
* [Technologies](##Technologies)
* [Setup](##setup)
* [Methodology](##Methodology)


## Homework_Assignment_Background (Latitude Analysis Dashboard with Attitude)

Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done. For this homework we'll be creating a visualization dashboard website using visualizations we've created in a past assignment. Specifically, we'll be plotting weather data.

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them. 

## Project_Task 

* The website consists of 7 pages total, including:

    1. A landing page containing:
        * An explanation of the project.
        * Links to each visualizations page.
    2. Four visualization pages, each with:
        * A descriptive title and heading tag.
        * The plot/visualization itself for the selected comparison.
        * A paragraph describing the plot and its significance.
    3. A "Comparisons" page that:
        * Contains all of the visualizations on the same page so we can easily visually compare them.
        * Uses a bootstrap grid for the visualizations.
        *The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
    4. A "Data" page that:
        * Displays a responsive table containing the data used in the visualizations.
        * The table must be a bootstrap table component. 
    5. The website must, at the top of every page, have a navigation menu that:
        * Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
        * Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
        * Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
        * Is responsive (using media queries). The nav must have similar behavior as the screenshots "Navigation Menu" section (notice the background color change).
    6. Finally, the website must be deployed to GitHub pages.


## Technologies
The project is created with:

* Bootstrap===4.3.1
* CSS

## Setup
1. To link directly to the latest Bootstrap release (https://getbootstrap.com/docs/4.1/getting-started/introduction/) 

## Methodology

1. Wrote code to create the following html webpages:
    * Main landing page(index.html)
    * Comparison's page(coparison.html)
    * Data page (data.html)
    * Latitude vs Cloudiness page (lat_vs_cloud.html)
    * Latitude vs Humidity page (lat_vs_humidity.html)
    * Latitude vs Temperature page (lat_vs_temp.html)
    * Latitude vs Windiness page (lat_vs_wind.html)

2. To visualize html page

    * Open index.html 
        1. Open with live server OR
        2. Open via local webserver.  
            * Open terminal, type: 
                ```python
                python -m http.server
                ```
            * In address bar, type:
                ```
                http://localhost:8000                                    

        * Below is a snapshot of the landing page for the assignment.

        <img src="docs/Resources/assets/images/final_hw_image.png" width="500" height="300">


