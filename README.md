# InfoVis Assignment 2

In this assignment, multiple visualizations were implemented from an [Online Sales Dataset](https://www.kaggle.com/datasets/yusufdelikkaya/online-sales-dataset).

In order to map an interactive choropleth map, a [geoJson dataset](https://raw.githubusercontent.com/holtzy/D3-graph-gallery/master/DATA/world.geojson) was also required.

### Animations and Interactions

As for interactions, the user can zoom in on the map using the wheel scroll, hover a country, generating a line around the country's shape to highlight it, as well as displaying a tooltip that provides the number of sold products and the country's name. A user can click in whatever country they wish to check the annual revenue trend on the bar chart below the map. They can also click any bar of the chart to filter the map per year available. There is also a shipment provider filter on the top left that will filter both the map and the bar chart to only include said shipment provider. If the user double clicks on a country, he will be taken to a more detailed view of shipments and a calendar heatmap.

An initial fade-in animation of the map was implemented, as well as a line animation in the sankey diagram available on the detailed view.

All the visualizations provide tooltips when hovering over the graph elements.

### Hosting and Deployment

This project's source code is available [here].

The live visualization can be seen [here].

If the live visualization is not working, please open this folder in VSCode and run the [LiveServer] plugin (be careful with https issues! use http if it does not work out of the box).
