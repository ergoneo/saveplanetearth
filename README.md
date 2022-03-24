# Project Title

Save Planet Earth (Final project for the Building AI course)

## Summary

Save Planet Earth is a tool that monitors the health of the forests, the woods and parks of our planet. This application can recognize any green zones and their characteristics based on high resolution satellite pictures. The aim of this project is to monitor the evolution of forests over time and to create awareness about the risk of the massive deforestations our planet is victim of.

## Background

Planet earth needs forests, woods and parks to prosper. Today planet earth is in danger due to human activities. Every year, big forests are cut down. Their size decreases at a frightening speed.

But who has a clear global view of the health of the green zones of planet Earth? Some international institutes may know, but at what extent. It's time to give awareness to everyone about the consequence of our behavior towards planet Earth.
This application will show to everyone the health states of each forest and highlight the green area which are deteriorating over the last years as well as those which are improving.
if thanks to this application, more people become more aware about the situation and some of them take concrete action, it'd be considered as a success
In the future, we can also think about a advanced version for environmental expert that will analyse more precisely the evolution of a forest over time.

## How is it used?

Today the project contains only one file README.md. This section will be updated as soon as there is a beta version.


## Data sources and AI methods

Data sources we need for this project is a data base of high-level resolution satellite pictures. There are different satellite images providers on the market. We need to do a market analysis to choose the most appropriate.
Also, the database needs to be updated regularly with up-to-date satellite pictures.

Using a combination of deep machine learning techniques and trained human mappers, we are combining high-resolution imagery and inexpensive cloud computing to create a comprehensive map of green zone on a wide-wide scale.
Training data from a well know country is used to tune the algorithm for a Forest classifier based on a convolutional neural network (CNN). The CNN can be created by modifying existing tools based on Xception and MobileNetV2 so that they could use satellite imagery.
Running the model over such a large area of high-resolution imagery is a huge task – several million images must be processed. We will user the open source tool created by Development Seed, chip-n-scale-queue-arranger, to manage the high-volume satellite imagery inference tasks.

## The process

*	Create a high-quality map of green zone in a country
*	Generate a training dataset
*	Create and tune a Forest classifier
*	Run the model in another country to identify candidate unmapped forests
*	Validate these predictions with people on the ground

## Challenges

This project is ambitious. The 2 main big challenges are to find a good satellite picture provider and to put in place a reliable infrastructure capable to treat high volume of images in acceptable timeframe.

## What next?

In order to upgrade the application, we would need the insight of forest experts in order to better understand what a forest is it, and by consequences, to be able to better model it. 


## Acknowledgments

* element of AI, course given by University of Helsinki. A must!
* Development Seed
