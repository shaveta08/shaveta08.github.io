# shaveta08.github.io

## Web Visualization Dashboard (Latitude)
Data is more powerful when we share it with others! I have used what I have learned about HTML and CSS to create a dashboard showing off the analysis we've done in a Dataset.

This website consist of 7 pages total, including:

### A landing page containing:
  * An explanation of the project.
  * Links to each visualizations page. There is a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.

### Four visualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.

### A "Comparisons" page that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
  * The grid is two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.

### A "Data" page that:
  * Displays a responsive table containing the data used in the visualizations.
  * The table is a bootstrap table component.
  * The data has came from exporting the .csv and converting it to HTML. used pandas for such purposes. Pandas has a nifty method approprately called to_html 
    that allows you to generate a HTML table from a pandas dataframe.

### The website at the top of every page, have a navigation menu that:
  * Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
  * Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
  * Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
  * Is responsive
  
## To Check This project in Action click Here: https://shaveta08.github.io/
