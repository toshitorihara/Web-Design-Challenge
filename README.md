# Web Visualization Dashboard (Latitude)

## Instructions
Create a visualization dashboard website using visualizations from weather data. In building this dashboard, create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

## 1. Landing Page
* An explanation of the project.
* Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.

## 2. Visualization Pages (4)
* A descriptive title and heading tag.
* The plot/visualization itself for the selected comparison.
* A paragraph describing the plot and its significance.

## 3. Comparison Page
* Contains all of the visualizations on the same page so we can easily visually compare them.
* Uses a Bootstrap grid for the visualizations.
* The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.

## 4. Data Page
* Displays a responsive table containing the data used in the visualizations.
* The table must be a bootstrap table component.
* The data must come from exporting the .csv file as HTML, or converting it to HTML. 
* Use Pandas to_html function to generate a HTML table from a pandas dataframe.

## 5. Navigation Menu
* With name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots "Navigation Menu" section (notice the background color change).

# Bonus
* Use a different dataset! The requirements above still hold, but make it your own.
* Use a Bootstrap theme (and tool like Bootswatch) to customize your website, and add extra visualizations.
* Use meaningful glyphicons next to links in the header.
* Have visualization navigation on every visualizations page with an active state.
