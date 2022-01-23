Build a dynamic dashboard to analyze human navel bacteria using JavaScript, Plotly, D3, HTML, CSS, and Bootstrap.

# Bellybutton_Biodiversity

# Purpose
The project builds an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. It will identify the top 10 bacterial species in their belly buttons to help in research of manufacturing sythetic beef. 

The interactive dashboard will review the data with:

* Display the Test Subject's  demographic information.
* Table displaying each key-value pair from the metadata JSON object on the page.
* Interactive dashboard such that when a new data was selected from the dropdown, the charts display the change
    * Horizontal bar chart with the top 10 OTUs found in that individual.
    * Bubble chart that displays each sample.
    * Gauge Chart with the weekly washing frequency of the individual.

The webpage is mobile optimized using the grid framework of BootStrap 3.3.7.

# Resources
* Data Source: ["Belly button samples data"](https://github.com/ramya-ramamur/Bellybutton_Biodiversity/blob/main/static/samples.json) information stored in a javascript file.
* Software/Libraries: HTML/CSS, JavaScript, Visual Studio Code 1.49.1, BootStrap 3.3.7, D3, Plotly 4.11

# Results

**Link to deployed webpage: ["Belly Button Biodiversity Dashboard"](https://ramya-ramamur.github.io/Bellybutton_Biodiversity/)**

**Initial page appearance when landing on the webpage**
The data on the page shows details about Test Subject ID No.:940

<img width="1168" alt="Screen Shot 2022-01-23 at 5 12 24 AM" src="https://user-images.githubusercontent.com/75961057/150681047-92a647cc-1b67-48d2-bb2f-ceaf15145657.png">
<img width="1151" alt="Screen Shot 2022-01-23 at 5 12 51 AM" src="https://user-images.githubusercontent.com/75961057/150681052-d87d6318-673b-4a91-a2fc-5b63220597f0.png">

**Filtered Data Example**
Page appearance when filtered with Test Subject ID No.:962. 
The information in the bar cart, gauge chart and bubble chart including demographic information changes with selection of "Test Subject ID No: 962" from the dropdown menu with hover feature active for bar and bubble charts. 

<img width="1169" alt="Screen Shot 2022-01-23 at 5 49 19 AM" src="https://user-images.githubusercontent.com/75961057/150681716-6f32f80a-a467-4f2f-af47-64fd5c6807c4.png">
<img width="1169" alt="Screen Shot 2022-01-23 at 5 49 51 AM" src="https://user-images.githubusercontent.com/75961057/150681719-f6ec9eba-94a6-4da2-99fc-9ff122d649af.png">
