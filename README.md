node-red-covid-status-by-country
================================

It gives a nice overview of the current covid status for the different countries or US states.

**Main features:**
- reproduction rate calculation (based on confirmed cases)
- sorteable (even based on distance for a selected country)
- relative metrics (in terms of million people)
- with one click on the retrieve button it refreshes the table with latest information

Here below an example of the output it produces.

![](https://aws1.discourse-cdn.com/business6/uploads/nodered/original/3X/d/6/d693ce6ffebb3e0a86d7dd749ed5a4ef278f9954.png)

Here below a description of the different columns shown in the table:

![](https://aws1.discourse-cdn.com/business6/uploads/nodered/original/3X/d/9/d91dfea0a5643fbd0fe9c1e515d3f9b71a4c016d.png)

This flow is also discussed in the Node-red forum under topics
*  [COVID-19 status by country](https://discourse.nodered.org/t/covid-19-status-by-country/28743)
*  [COVID-19 status by country (update)](https://discourse.nodered.org/t/covid-19-status-by-country-update/32602)

# Installation Warning

Just importing the flow in node-red doesn't always immediately work due to an issue with the `node-red-node-ui-table` node.
If you encounter this issue then an easy fix for it can be found [here](https://discourse.nodered.org/t/covid-19-status-by-country/28743/19).
