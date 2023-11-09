# Final Project - ESS 314 2023

##Scenario: 
As a USGS-employed geophysicist, you have been selected to perform a geophysical study of the Long Valley Caldera, CA. The Long Valley Caldera formed 760 ka years ago when the eruption of 600 km3 of material, now called the Bishop Tuff, resulted in 1-2 km of subsidence into the evacuated magma chamber. Since the supereruption, additional eruptions at 500 ka, 300 ka, and 100 ka centered on a resurgent dome in the caldera. More recently, volcanic activity shifted westward, creating Mammoth Mountain (a popular ski area for Californians) on the southwest margin of the caldera. Since 1978, Long Valley Caldera has experienced unrest, with earthquake swarms, uplift of the resurgent dome, and CO2 emissions near Mammoth Mountain. Recently, the scientific debate has proposed 2 potential interpretations of the unrest: an active hydro-geothermal activities or an active magmatic intrusion in the shallow subsurface (). In light of this unrest, it is your job to find out if subsurface anomalies could lead to more unstable activities and to participate in this debate.

For this study, you will aim to (1) interpret the subsurface layers in light of the geologic history of the area and (2) look for any signs of renewed volcanism. You will use the instruments at your disposal – a seismic unit, a gravimeter, and a magnetometer – to systematically explore the area. 

# Assignment Overview 
You will receive two different data sets from the survey efforts. You will begin with analyzing the seismic reflection and refraction data, followed by gravity and magnetic data sets of the same area. 

Treat the audience of your report and presentation as members of the U.S. geological survey, geotechnical engineering, or a broad academic audience.

## 1. Computational workflow as a Python notebook:
* One or several notebooks that demonstrate the calculations and the figures. Providing the script of your work is a central element to research reproducibility and is recommended (or imposed) by scientific journals. Provide a notebook that is well-organized and commented on. Follow the structure of the report under the section Methods&Results and use the notebook to explain your analysis. Upload the notebook itself, rendered with all the figures, on canvas. 
* Save the figures from the notebook in PNG and add them to your report.
* Import all important python packages used in the lab (pyrocko, harmonica, verde, matplotlib, numpy, pandas, …) 


## 2. Report:
1. Introduction to the problem
    * Problem Statement and why geophysical surveys will help the analysis. You may cite scientific journals or other USGS reports to support the problem statement.I
    * What kind of geophysical survey was performed, and what is the data availability (brief statement)? Describe the arrays of sensors and the sources used.
    * A brief overview of this report.
    * < 0.75 page
2. Methods&Results (4 pages max)
    * Seismic reflection (1 page)
    * Seismic refraction (1 page)
    * Gravity (1 page)
    * Magnetics (1 page)
    * For each method, write a concise 0.5-page summary on how these methods work and what particular aspect of the data analysis can help constrain the image.
    * Each survey yields an individual model/image.
    * Each result should have a short text describing the figure. It is not an interpretation of the results.
    * Each method should include 2-3 sentences about strengths and weaknesses of the methods/data in imaging the subsurface.
3. Synthesis - Discussion ( 1 page)
    * Conclude on your interpretation of your multi-disciplinary results to characterize the magmatic system. Conclude what is the most likely single model that could be derived from all images/models.
    * Discuss the potential sources of errors or limitations in the survey and what could be done next time to provide a better model.
    * This is a place to showcase sophisticated “critical thinking”. For instance, pose and answer the question “how are the three images consistent with each others?” 
4. Summary conclusion (0.3-0.5 page)

**Figures** should be clearly labeled - low margins - font size of > 10 pts in the text form. Each axis should have a label. Number the figures and reference them at least once in the main text.

**References** should be listed at the end of the doc following a standard citation format. Examples of how to get these references from Google are below.

Google Scholar does not give Digital Object Identifier (DOI); you must click on the paper and find it. It should be like this: https://doi.org/10.1130/GES01053.1

**Organization**: use numbered sections and subsections (1. Introduction, 2. Methods&Results, 2.1 Seismic Reflection, 2.2 Seismic Refraction, …)

**Scientific Writing help**: read the docs uploaded on Canvas:
	Help_ScientificWriting_XXX.pdf

Use LaTeX, Google Docs, or Microsoft Word and upload a PDF to Canvas. Use 12-point type, with 1” margins and single spacing.


## 3. Oral presentation 
Support your report with a 7-minute presentation. Add all figures to the presentation. Convince us of your analysis. Consider this as a presentation to a scientific conference or symposium. Practice presentation clarity, effectiveness of the slides, and delivery quality. Speak clearly, articulate, steady pace, look at the audience, and react to the audience’s reactions.
Use PowerPoint formats to upload to Canvas.

**Guidelines for the Preliminary Report on Seismic Data**: 
A mid-point check-in of the project is assigned to assess and ensure progress over the final project. The mid-point check-in does not require the entire project, you are expected to have completed at least 50% of the project (notebook, report, presentation slides). The midpoint check-in is a draft of your final project. Submit all three pieces on Canvas, and we will provide written feedback. For in-person feedback, please attend the following office hours.




##  Rubric for grading. 
100 points for the final project.
50 points for the mid-point check-in.

Written report (40%):
Written mechanics (20%): grammar, spelling, referencing, etc. 
Clarity and flow of argument (20%): is your text organized? Does each paragraph feed off of earlier paragraphs and facilitate later ones? Is some information “extra” – i.e. do you have a paragraph that doesn’t contribute to the point of what you’re writing, etc. 
Strength of Support (25%): is your argument a sound one – i.e., is it supported by the data and figures you have available in a clear, direct fashion? Have you made a clear distinction between observations and interpretations? Do you convey clearly the things you know for sure versus those you must infer, etc. 
Sophistication of argument (15%): a simple argument supported by simple evidence can be sound, but we are also looking for indications that you have taken things a step or two beyond this intellectually. Consider the geologic setting. You can say, “this layer is composed of loose sediment because the seismic velocity is 2000 m/s,” or you can say, “This layer is composed of loose sediment because the seismic velocity is 2000 m/s, and glaciers deposited a lot of debris in the area many years ago.” The second is a much stronger argument (and is the difference between an “A” and a “B”). 
Adherence to guidelines (5%): You were asked 6 pages, but you wrote 12! Did you include all the required sections in your report? 
Effectiveness of your revisions (15%): how thorough a job have you done when revising your text in response to my comments and your new data? Did you incorporate the specific comments provided to you the first time to improve on the final?

Notebook (30%):
Notebook organization (30%): between each section, import modules on the top cell, make a cell per figure etc, and remove unused cells.
Commenting to enable reproducibility (20%): can your sibling or another peer in STEM re-run the notebook and understand the steps (even without understanding geophysics in general)
Correctness of the analysis (50%): did you follow the guidance from the lab and produce a correct analysis? Even if the final image is not unique, your notebook should demonstrate the correct workflow.

Presentation (30%):
Effectiveness of the presentation (40%)
Q/A discussion (20%)
Simplicity - clarify of the slides (20%)
Presence on stage and eloquence (20%)
