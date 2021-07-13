# plotly_deployment

## Overview

Developing a customizable dashboard with a bar, bubble, and gauge chart for different sorts of bacteria in an HTML/Javascript project. The dashboard can be filtered using a drop-down menu with different bacterium IDs. The data shows that a limited number of microbial species (referred to in the study as operational taxonomic units, or OTUs) were found in more than 70% of persons, while the rest were uncommon.

### Results

To read in samples, use the D3 library. json.

To present the top 10 OTUs detected in that individual, use a horizontal bar chart with a dropdown menu.

- Use sample_values as the values for the bar chart.
- Use otu_ids as the labels for the bar chart.
- Use otu_labels as the hovertext for the chart.

Create a bubble chart that displays each sample.
- Use otu_ids for the x values.
- Use sample_values for the y values.
- Use sample_values for the marker size.
- Use otu_ids for the marker colors.
- Use otu_labels for the text values.

Display the sample metadata, i.e., an individual's demographic information.

Display each key-value pair from the metadata JSON object somewhere on the page.

### Summary

First, we completed panel for demographic information and now needs to visualize the bacterial data for each volunteer. This Customize Dashboard will help to identify the top 10 bacterial species in their belly buttons and volunteers will be able to identify whether that species is found in their navel.
