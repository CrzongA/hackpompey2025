# Hackpompey 2025: The Lonely Dashboard

This is my submission for [Hackpompey 2025 hackathon](https://hackpompey.co.uk/). 

The original goals of this project is to build a comprehensive dashboard that visualizes air quality metrics for the Portsmouth International Port. The dashboard should include the following features:

- heatmap visualization of historical data

- prediction of air quality metrics (CO2 etc.) in the next few hours

- display the correlation between ship movements and air quality changes

The name of this project came from my realization towards the final moment of this hackathon that I am not going to achieve what I set out to do, and by the end of the hackathon I have only managed to complete the first target :). Nonetheless, I have learned a lot from this experience and I am working on improving this project so that more helpful information and insights can be extracted from these data.

This is a work in progress.

## Modules
Visit the module folders for a more detailed readme.

`/app`
- Next.js-based web application
- [x] Display historical CO2 data in a heatmap
- [ ] Display ship movements
- [ ] Display wind speed, direction 
- [ ] Correlation factor between ship movement and air quality


`/data-server`
- Two submodules:
    - Jupyter notebook for training Machine Learning model
    - Node.js server to serve as a CO2 prediction agent 
