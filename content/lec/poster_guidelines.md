---
title: "Poster Guidelines"
date: '2017-11-26'
output:
  blogdown::html_page:
    toc:true
---

# Quick links to content on this page
* [Structure](#structure): Templates and sections
* [Aestetics](#aestetics): Font, tables, graphics, colors, logos, 
* [Printing](#printing): Guidance, location and prices
* [Evaluation](#evaluation-criteria): grading rubric
* [Examples](#examples): Selected examples

# Structure

### Template
* Build your poster using a [powerpoint template](http://www.posterpresentations.com/html/free_poster_templates.html), not Google Slides. 
    - Do not do a trifold tabletop template. 
* Choose either a three, or four column layout. 
* Choose the correct scaling. 
* Biology Student Research Symposium [[website]](https://www.csuchico.edu/biol/research/student_research_symp.shtml) - Additional templates and guidelines included.



### Sections
1. Abstract/introduction
2. Sample characteristics
3. Analysis methods
4. Results
5. Conclusions/discussion
6. Implications
7. References


# Aestetics

### Font size
* Readable from 10 feet
* This tends to be at least 18-20 pt font. If using a template provided

### Tables
* Build them in Excel, or PowerPoint tables directly


### Graphics
* Not copy/paste from R, it won't scale up well. 
    - Finalize the plot, then save it to disk
    - Save the file larger rather than smaller, then manually shrink down in PPT
    - Specify height and width in inches
    
```
postscript("filename.eps", width=5, height=3) # open the graphics device.
plot(iris$Species) # your plot goes here
dev.off() # this closes the graphics device
```

### Campus Logos
Your poster is a professional publication. It should reflect your campus properly and following guidelines (where they are listed). Every campus has official logos, colors and instructions on how to correctly use these. Below I have linked the ones I could find for Chico State. 

* [[University Naming]](https://www.csuchico.edu/style-guide/visual/naming.shtml)
* [[Color Palette]](https://www.csuchico.edu/style-guide/visual/colors.shtml)
* [[Logo and Seal]](http://www.csuchico.edu/pub/graphic-standards/index.shtml)
    - This page is not fully developed yet, only the seal is available for download on this page. 
    - [[Other unofficial logos]](http://ancul.us/chico-state-logo/). Note that the use of the wildcat is not allowed unless you are discussing Athletics. Stick to using the Seal, or flame logo. 




### Colors
* Colors are good - but stick to a theme/pallet. 
    - Make the colors meaningful
* Use matching theme colors in graphics
* R Cookbook guide for colors in ggplot2: http://www.cookbook-r.com/Graphs/Colors_(ggplot2)/ 



# Printing
* Don't wait until the morning of to print - this is ESPECIALLY true in Spring when there are multiple poster symposiums being conducted. 
* You can print in B&W, and any color graphics can be printed on 8x11 and taped onto the poster. 
* Don't spend a fortune!

_Prices are student reported as of Fall 2016._

* Staples ($65)
* Metagraphcs $50 36x48 --still pricey
* Ellis Art (downtown and on Esplanade) $30
* Kinko's downtown, B&W $10


# Evaluation Criteria
I use the following criteria to score posters. You can also [[download]](poster_rubric.docx) the rubric as a Word doc for printing. 

* **Appearance**
    - Display attracts viewer's attention.
    - Words are easy to read from an appropriate distance (3-5 feet).
    - Poster is well organized and easy to follow.
    - Graphics and other visuals enhance presentation.
    - The poster is neat and appealing to look at.
* **Content**
    - Content is clear and easy to understand.
    - Purpose of model (question being addressed) is stated clearly.
    - I understand why someone might be interested in the model results.
    - There is enough detail about methods (e.g., creating new variables) for me to understand the model and results.
    - The sample characteristics are fully described.
    - The approach taken is appropriate for the problem and technically sound.
    - Conclusions are stated clearly.
    - Conclusions are supported by model results.
    - Limitations of the study are clear. 
* **Presentation** 
    - Presenter's response to questions demonstrated knowledge of subject matter and project
    - The presenters conducted themselves professional during the presentation.
    - It was clear that all team members understood what was being presented and had an equal contribution to the data analysis. One member did not dominate the presentation and questions.
    
    


# Examples
A selection of sample posters, class projects have comments regarding what made them stand out, and what could be improved. 

<button data-toggle="collapse" data-target="#plot">Show/Hide Professional Conference Presentations</button>
<div id="plot" class="collapse">

* [Patterns of Sexual Experience Among an Urban Sample of Latino and African-American 9th Grade Students](ExamplePosters/prof/2013 Jeffries APHA Sex patterns.pdf) _Jeffries, RA., De Rosa, CJ., Moulton, B., Chung, EQ._
* [Sexual Identity and Associated Factors Among and Ethnically Diverse Sample of 9th Grade Public School Students](ExamplePosters/prof/2014 Viola SRA Sexual Identity.pdf) _Viola, R., Jeffries, RA., Moulton, B., De Rosa, CJ._
* [Pre-sexual behaviors as predictors of sexual risk in adolescents: Examining alternate outcomes in sexual health education programs](ExamplePosters/prof/2017 Moulton APHA Presex proxy.pdf) _Moulton, BD., Donatello, RA., Rohrbach, L., Afifi, A., Meyer, KI., Leon, P., Lau, C._
* [Implementing a Flipped Classroom and Active Learning Techniques in General Chemistry to Augment Student Success at a Mid-Sized Rural University](ExamplePosters/prof/2017 Smith CHEM ED.pdf) _Smith, M., Aguilar, R., Cherrette, V., Rose, A., Crane, J., Park, C., Bladorn, E., Mills, H., Sherry, S., Chatha, C., Park, H., Dailey, H., Donatello, RA., Wasinger, E._

</div>



<button data-toggle="collapse" data-target="#grad">Show/Hide Graduate class projects</button>
<div id="grad" class="collapse">

* [Moving Away From BMI: Lifestyle and Biological Factors Impacting Health](ExamplePosters/grad/2016 Moving away from BMI.pdf) _Brooke,C., Corona,J.,Kessner S.,Lona,I._
    - Great additions to the univariate plots of BMI and Cholesterol. Tables are clean, could use bigger font. Sample characteristics only a list of variables. Not enough info on analysis methods, or explanation of Figures 2 and 4.
* [Do Field Dimensions Affect Baseball outcomes?](ExamplePosters/grad/2016 Baseball field dimensions.pdf) _Stolenberg R., Williams K., Harris A._
    - Excellent use of whitespace, colored tables that match the theme. Plots are difficult to read, font size is great, but paragraphs are harder to read than bullet points. 
* [Effects of Childhood Social Support on Trauma](ExamplePosters/grad/2016 Social support and childhood trauma.pdf) _Hostler, M., Thornton A., Wong R._
    - Clearly laid out variables of interest and RQ's. Good use of pie charts. The 3D scatterplot is not helpful. Model results presented in a nice table, but not explained. 
* [Using 2010 U.S. Census Demographics to Determine a Predictor for Beer and Wine Consumption](ExamplePosters/grad/2016 Census Alcohol.pdf) _Ellis, C., Esposito, C., LaGrange, A._
    - Great use of maps, model comparison table in the bottom middle. Bullet points clear and easy to read. Univariate summary statistics very clearly laid out. 

</div>


<button data-toggle="collapse" data-target="#ug">Show/Hide Undergraduate Projects</button>
<div id="ug" class="collapse">

* [The Associations Between Familial Relationships, Daily Activities and Delinquency in Adolescents](ExamplePosters/ug/PDS Guetta.tif) _Guetta, R._
    - Very clearly laid out RQ's and introduction. Discussion connects to current literature. 
* [Trends in Avian Influenza at Howard Slough](ExamplePosters/ug/2016 Avian Influenza.pdf) _Aguilar, R., Antonio, A., Balkow, N., Dehoney, T., Ling, D., Saenz, J., Urlie, L., Cline, T._
    - Good balance between tables and graphics, cute duck. Results clearly explained using N(%) in text.
* [The Effects of Voter Demographics on the 2016 Primary Elections](ExamplePosters/ug/2016 Primary Election.pdf) _Jordan, A., Arriaza, L., Ejaz, N., Loeblich, A., Wain, C._ 
    - Watermarks on bottom corners make words difficult to read. Table under results not made in Excel. Not easy to follow direction of story 

</div>





