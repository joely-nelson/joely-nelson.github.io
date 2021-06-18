---
layout: post
title: Vaccine Impact Modeling Tool
---
***Capstone Project.*** *June 17, 2021*
<br>
*By Joely Nelson, Kenny Krivanek, Joe Ammatelli, and Tevin Stanley*

The Vaccine Impact Modeling Tool is an interactive modeling tool, given user input, retrieves COVID related data, models pandemic outcomes, and displays them on a global map.

<iframe width="560" height="315" src="https://www.youtube.com/embed/ePIrc7szvMk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Made as the final project for CSE 482B: Capstone Software Design to Empower Undeserved Populations at the University of Washington.

[Github](https://github.com/joely-nelson/VaccineModelingTool)

<!-- more -->
In December 2020, the FDA issued the first emergency use authorization for the use of COVID-19 vaccines. A natural question that arose was the best way to administer vaccines to reduce severe pandemic outcomes. Although tools exist to display models or up-to-date COVID-19 data, few tools incorporate both. To help with this situation, we designed an interactive modeling tool which, given user input, models pandemic outcomes and displays them on a global map. The Vaccine Modeling Impact Tool allows users to select and adjust target parameters and useful data to visualize. They can view an interactive global map of the model’s output with more data available on zooming and clicking. We designed the visualization front end, a data scraper to retrieve current COVID-19 data, a model to simulate pandemic outcomes, and a server to handle user requests and data flow. We aimed for our project to be user-friendly enough that someone with only basic public health knowledge could use our tool and could gain useful insights.

My main part in this project was designing a simple model to be used for the visulization, and designing the framework for a model tempelate that other modelers could use to write their own models in Python to be displayed on the map.

For this project we wrote a paper detailing our process. You can download the pdf here: [CSE_482B_Final_Paper_Vaccine_Modeling_Impact_Tool.pdf]({{file name='../documents/CSE_482B_Final_Paper_Vaccine_Modeling_Impact_Tool.pdf'}})

