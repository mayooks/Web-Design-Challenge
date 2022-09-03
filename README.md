# Web-Design-Challenge
In this work I designed a 4 page website dashboard that shows visualisation of the effect of latitutude on four weather parameters. These are temperature, humidity, windspeed and cloudiness. To get the weather data for 500 cities,  an API call was made to the OpenWeatherMap.org website using Pandas. The data recieved from the website was then converted into as CSV file that was used to extract the data for the visualisation. Finally, the website was deployed to GitHub Pages, with the website working on a live, publicly accessible URL . e.I used CSS media query that Bootstrap and @media for the navigation bar as well as to ensure website is responsive and works on all window widths or sizes.
The website has a Navbar that contains links to other sections of the website. The four main pages of the wesite are
<ul>
  <li>Home</li>
  <li>Comparisons</li>
  <li>Data</li>
  <li>Plots</li>
</ul>
 
## Home
The Home page is the landing page. As the user get on the page they can see a large visualisation of the latitude vs max temperature. On the side of it there are 4 thumbnails of the 4 visualisation that can be diplayed on the landing page. The other 3 visualisations are latitude vs: max temperature, humidity, cloudiness, or wind speed.Clicking on each thumbnail takes the user to that visualization without going away from the home page

## Comparisons

Comparisons page which contains all of the visualizations on the same page so they can easily be compared with each other

## Data

Data page that displays a responsive table containing the data used in the visualizations

## Plots
The plots is where the use can select 

Landing Page:

Four visualisation pages - latitude vs: max temperature, humidity, cloudiness, or wind speed. With links to each visualizations page. Clicking an image takes the user to that visualization. And visualization navigation on every visualization page with an active state for the one you're currently on.

Comparisons page which contains all of the visualizations on the same page so they can easily be compared with each other:

Data page that displays a responsive table containing the data used in the visualizations. Table created from cvs file exported into HTML using Python and Pandas.

At the top of every page, the website must have a navigation menu with the following elements:

It should have the name of the site on the left of the navigation bar, allowing users to return to the landing page from any page.

It should contain a dropdown menu on the right of the navigation bar, named "Plots," to provide links to each individual visualization page.

It should provide two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.

It should be responsive (using media queries). The navigation bar must be similar to the screenshots in the "Navigation Menu" section (notice the background color change).

