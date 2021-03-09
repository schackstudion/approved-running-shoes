# approved-running-shoes

A video-based tool that identifies forbidden shoes in running competitions
Building AI course project

## Summary

In 2020 World Athlecis introduced rules for what types of running shoes that are approved in different types of competitions. It's impossible to do this manually in big events with thousands of runners. The organizers need a machine learned and video based AI-tool. 

## Background

The rules have been modified frequently, and during the first year, organizers did not take them into account. An AI-based tool would need to:
1) Get access to photos from the race
2) Identify runners with their BIB-number (this already exists)
3) Connect the runners with their shoes
4) Identify the shoe model and check it from a list of approved shoes (since the rules are constantly changing, it's not enough to identify if the shoe is approved or forbidden)

## How is it used?

Organizers setting up cameras on races, and getting lists of runners whose shoes need to be checked.

![Cat](https://github.com/schackstudion/approved-running-shoes/blob/main/LondonMarathon2017.jpg)

## Data sources and AI methods
The AI-tool learns from photos where humans have labelled different shoes with their models. Easy to make a huge enough list as a collaboration.

## Challenges

None.

## What next?

A programer.

## Acknowledgments

[Photo from London Marathon by Chris Mole] (https://www.flickr.com/photos/zapmole/) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
