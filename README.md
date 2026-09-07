# Ichnaea-MST
Ichnaea-MST is an autonomous Machine Learning tool for tracing microbial contamination sources. Built by and for environmental microbiologists, it provides R‑based models powered by H2O, offering local or Shiny‑GUI access and an easy, accessible workflow with no prior ML experience required.

Ichnaea-MST
A Machine Learning Tool for Microbial Source Tracking, designed by environmental microbiologists, for environmental microbiologists.
What is Ichnaea-MST? 
Ichnaea-MST is a novel, autonomous tool developed to trace the origin of microbial contamination in various environmental matrices, offering a more powerful and user-friendly experience.

Key Features:

✅ Built in R: A full suite of R scripts tailored for training and classification tasks.

✅ Powered by H2O: Utilizes the H2O framework for robust performance.

✅ User-Friendly: Designed for users with little to no machine learning experience.

✅ Flexible Access: Use locally via RStudio or remotely through a Shiny-based GUI.

Who Is It For?
Whether you're a seasoned microbiologist or just starting to explore machine learning, Ichnaea-MST provides a straightforward, accessible entry point into Microbial Source Tracking (MST).
Why choose Ichnaea-MST?

✅ Developed by experts in environmental microbiology.

✅ No prior coding or ML knowledge required.

✅ Supports reproducible, transparent MST workflows.

How to Use:

✅ Local Use: Run the R Notebooks in RStudio, an IDE for R or use the tool via our web-based Shiny GUI.

In this repository you will find the following files: 

📙 Ichnaea‑MST User Manual.pdf: contains the complete user manual for both the web application and the two R Notebooks intended for local execution. 

The three source codes: 

📦 Ichnaea_MST.zip, which comprises the Shiny‑based web application.

🧮 R Notebooks: Module1.Rmd and Module2.Rmd. 

📊 A results file, Report_Ichnaea_MST.html, provides an example of a report generated from a binomial classification. The classification outputs include two scenarios: one without applying T90 decay, using the full set of MST markers, and another using the reduced set of MST markers, in which the classification incorporates a hypothetical natural decay (a T90 of 48 hours and a residence time of 24 hours).

⚠️ In the results report, the data tables from the two EU research initiatives—TOFPSW (2001–2004, EVK1‑CT‑2000‑00080), Tracking the Origin of Faecal Pollution in Surface Waters, and AQUAVALENS (2012–2016, Grant 311846), Protecting the Health of Europeans by Improving Methods for the Detection of Pathogens in Drinking Water and Water Used in Food Preparation—have been deliberately omitted. The same note is included in the description of the Report_Ichnaea_MST.html file.

## Scientific Publication
The methodological foundations, implementation, validation, and potential applications of Ichnaea-MST are described in the following scientific article:

> Méndez, J., Monleón, A., Rodríguez, A., & Blanch, A. R. (2026).
> **Ichnaea-MST: An automated machine learning tool for Microbial Source Tracking providing prediction of faecal source of contamination in water.**
> *Environmental Management: Smart Solutions, 1*(1), 100002.
> https://doi.org/10.1016/j.jemss.2026.100002


🔗 **Access the article:** [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S3117649626000026)
If you use Ichnaea-MST, its source code, or its associated workflows in your research, please cite the publication above.
