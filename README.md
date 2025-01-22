** Belly Button Biodiversity Dashboard
* Project Overview
This project is an interactive dashboard that visualizes microbial data from the Belly Button Biodiversity dataset. The dataset catalogs microbes found in human navels, highlighting that a small number of microbial species (OTUs) appear in over 70% of individuals, while others are rare.

* The dashboard includes:

A horizontal bar chart displaying the top 10 OTUs for a selected individual.
A bubble chart visualizing all microbial samples for an individual.
A demographic info panel showing metadata for the selected individual.
An interactive dropdown menu to update the charts and metadata dynamically.
Deployment on GitHub Pages for public access.
Technologies Used
JavaScript (D3.js & Plotly.js) – for data fetching and visualization.
HTML & CSS – for structuring and styling the dashboard.
GitHub Pages – for hosting the final project.
Dataset Source
The dataset is fetched dynamically from:
https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json

* Features
Bar Chart
Displays the Top 10 OTUs for the selected individual.
Uses sample values as the bar lengths.
Labels bars with OTU IDs and shows OTU labels as hover text.
Bubble Chart
Plots OTU IDs on the x-axis and sample values on the y-axis.
Bubble sizes correspond to sample values.
Colors represent different OTU IDs.
Hover text displays OTU labels.
Metadata Panel
Displays demographic details of the selected individual.
Updates dynamically when a new individual is selected.
* Deployment
The dashboard is deployed on GitHub Pages:
 - Go to the "Settings" tab of your repository.
- Scroll down to the "Pages" section on the left sidebar.
- Under "Source", select the branch you want to use (usually main) and the folder (typically / (root)).
- Click "Save".

🔗 Live Dashboard

Repository
🔗 GitHub Repository

* File Structure
bash
Copy
Edit
/belly-button-challenge  
│── index.html            # Main HTML file  
│── static/  
│   ├── js/  
│   │   ├── app.js        # JavaScript for data fetching and visualization  
│   ├── css/  
│   │   ├── style.css     # Optional styling  
│── samples.json          # Provided dataset (not used directly, fetched from URL)  
│── README.md             # Project documentation  
How to Run Locally
Clone the repository:
bash
Copy
Edit
git clone https://github.com/YourUsername/belly-button-challenge.git
Open index.html in a browser.
* Acknowledgments
Dataset: Rob Dunn Lab - Belly Button Biodiversity
Libraries: D3.js, Plotly.js
