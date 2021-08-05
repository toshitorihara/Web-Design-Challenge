# Web Visualization Dashboard (Latitude)

## Instructions
Create a visualization dashboard website using visualizations from [**weather data**](https://github.com/toshitorihara/python-api-challenge). In building this dashboard, create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

<p align="center">
  <img src="https://github.com/toshitorihara/Web-Design-Challenge/blob/main/visualizations/landingResize.png" height="75%" width="75%">
  <img src="https://github.com/toshitorihara/Web-Design-Challenge/blob/main/visualizations/landing-sm.png" height="24%" width="23.1%">
</p>

### 1. [**Landing Page**](index.html)
* An explanation of the project with links to each visualization page.
* There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.

### 2. **Visualization Pages**
* A descriptive title and heading tag: [**max temperature**](max_temperature.html), [**cloudiness**](cloudiness.html), [**humidity**](humidity.html), and [wind speed](wind_speed.html)
* The plot/visualization itself for the selected comparison.
* A paragraph describing the plot and its significance.

### 3. [**Comparison Page**](comparison.html)
* Contains all of the visualizations on the same page so we can easily visually compare them.
* Uses a Bootstrap grid for the visualizations.
* The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.

### 4. [**Data Page**](data.html)
* Displays a responsive table containing the data used in the visualizations.
* The table must be a bootstrap table component.
* The data must come from exporting the [**.csv file**](Resources/cities.csv) and converting it to [**.html file**](Resources/cities.html). 
* Use Pandas to_html function to generate a HTML table via [**.ipynb file**](Resources/csv_to_html.ipynb).

### 5. Navigation Menu
* With name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Using media queries via [**CSS**](style.css) to make responsive behaviors i.e. change background color at smaller size screen.
---
### Bonus
* Use a different dataset! The requirements above still hold, but make it your own.
* Use a Bootstrap theme (and tool like Bootswatch) to customize your website, and add extra visualizations.
* Use meaningful glyphicons next to links in the header.
* Have visualization navigation on every visualizations page with an active state.
