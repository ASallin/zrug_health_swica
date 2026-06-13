# R meets Health: Meetup @ SWICA

[TODO asa/sereina] The Zürich R User Group is happy to invite you to its next meetup on **R meets Health**. The meetup is generously sponsored and hosted by SWICA Organisation de Santé in Winterthur. 

## R and Health

[TOPOLISH asa/sereina] Switzerland has some of the best health outcomes in the world and one of the most expensive systems to run. Making better use of health data is central to improving population health and keeping costs in check, and R plays a growing role in both.

This evening, we look at R and healthcare from three angles: how a major health insurer uses data to shift towards value-based care, how the Swiss Health Observatory uses R to plan and allocate resources across cantons, and how Swisstransplant uses statistical modelling to understand and predict organ transplants.

Join us for an exciting, multi-faceted evening on analytics in healthcare, and for the apéro!

<br>

## R for an efficient and qualitative health care system

[TODO asa]Eva Blozik, Head of the Healthcare Management at SWICA, will be opening the evening with a brief introduction on how data are used to improve our healthcare system. She will explain the importance of sound data analysis for value in healthcare from an insurance perspective.

<br>

## Joint keynote talk 1: R for health policy planning - from Copy-Paste to Pipelines (Jonathan Zufferey and Reto Jörg, OBSAN)

#### Cantonal health reports
Every five years, the Swiss Health Observatory (Obsan) produces analyses based on the Swiss Health Survey (SHS), providing each canton with detailed insights into the population's health status, health behaviours, and healthcare utilisation.
In the past, these analyses were published in reports that were painstakingly created by exporting SAS analyses into Excel and then manually inserting them into Word — a tedious process that had to be replicated for every single canton. In 2024, we transitioned to a fully integrated and automated workflow using R and Excel. This shift enabled us to simultaneously generate both a [web-based output] (kgr.obsan.ch) and a pdf report. 
This presentation reviews this journey and the adopted methodology.

<br>

#### Primary Care Monitoring System
This project examines regional disparities in access to primary care services in Switzerland using a Floating Catchment Area (FCA) approach developed by the Obsan. Healthcare provider capacity is estimated from health insurance claims data, while healthcare demand is modelled using population characteristics and commuter flows. Accessibility is assessed using travel times derived from road network data.
The presentation will highlight selected preliminary findings while focusing on the technical challenges given the existing infrastructure at the Obsan and discuss how DuckDB was leveraged to efficiently process large-scale data.

*Jonathan Zufferey is a demographer by training and holds a PhD from the University of Geneva. Reto Jörg is a political scientist with a postgraduate diploma in applied statistics from ETH Zürich. Both work as senior researchers at the Swiss Health Observatory (Obsan), where they spend their days turning large amounts of healthcare data into somewhat smaller amounts of insight. Together, they are responsible for the Swiss Health Care Atlas, a national platform tracking regional variations in healthcare use across more than 100 indicators. In their joint talk, they present two further use cases showing how they use R to automate health reporting and build scalable data pipelines.*

<br>

## Keynote 2: R for predicting kidney transplant success ([Simon Schwab](https://www.statsyup.org/), Swisstransplant)

In Switzerland, 292 deceased-donor kidney transplants were performed in 2025, while over 880 patients remained on the national waiting list at the end of the year. Although kidney transplantation has excellent outcomes, graft loss remains a major concern for patients and clinicians.
In this talk, I present the KIDMO project (Kidney Prediction Model), a statistical model to predict graft loss. I will explain the model development and validation pipeline. I also demonstrate how these clinical prediction models can be translated into practical tools, including an R package and an online risk calculator built with Shiny, Quarto, and Posit Connect Cloud. The full workflow is simple, reproducible, and based entirely on freely available tools.

*Simon is a statistician at Swisstransplant and a lecturer at the University of Zurich, where he teaches clinical biostatistics to medical students. He holds a PhD in Health Science and a postgraduate diploma in Statistical Data Science (both from the University of Bern).*

<br>

# Organisation

- Date: **16.09.2026**
- Place: **Hotel Banana City, Winterthur**

  - 18:30 opening doors, registration
  - 19:00 Introduction (asa, sereina)
  - 19:05 Talk Eva
  - 19:15 Talk Obsan (20mn + 10mn questions)
  - 19:45 Talk Simon (20mn + 10mn questions)
  - 20:15 apero
  - 21:30 closing



> Registration: link to Meetup
