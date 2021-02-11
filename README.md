# Mushroom Classification
---
![](/presentation_images/mushrooms.png?raw=true "Example Images")
## Introduction
---

As any wild mushroom forager knows, mushroom identification can often be difficult and time consuming. Currently, several apps exist to address this problem: most of them allow a user to upload a picture and then return a prediction of the mushroom's variety or edibility. While many are fairly accurate and can be useful tools, the flaw that these apps all share is their reliance on internet.

Most applications for image or speech recognition run on neural networks. The average neural network uses more computing power than a smartphone is capable of, so these applications relay the data (e.g., the image, your voice) via internet to external servers for processing. Since most mushroom foraging takes place in the woods, where cell service is inconsistent at best, current mushroom identification apps do not meet the needs of foragers who wishing to idenitfy their finds on the go.

My objective was to create a mushroom image classifier light-weight enough to be operated on a smartphone, without the need for external servers. 

## Data
---
The dataset for this project was comprised of labeled mushroom images I scraped from four mycology websites and Google image searches. Before cleaning there were over 3,400 edible mushroom images and about 2,500 poisonous images. For more details on data collection, see the **scrapers** folder 

To ensure my model was trained on useful data, I removed any image that was too small, had poor resolution or had a main forus that was not a mushroom. After cleaning there were about 3,100 edible images and 2,250 poisonous images. Below are some examples of images that were removed from the dataset.
![](/presentation_images/removed.png?raw=true)

## Methodology
---
The first step of this project was to create a strategy for optimizing my data. Neural networks perform best 
## Results
---
