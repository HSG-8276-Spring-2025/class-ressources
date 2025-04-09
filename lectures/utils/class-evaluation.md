---
id: class-evaluation
title: Class evaluation
sidebar_label: Evaluation

---

## Grading

<center><style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin:0px auto;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-ul38{position:-webkit-sticky;position:sticky;text-align:left;top:-1px;vertical-align:top;will-change:transform}
.tg .tg-1wig{font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-rz9m{position:-webkit-sticky;position:sticky;text-align:center;top:-1px;vertical-align:top;will-change:transform}
.tg .tg-amwm{font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
@media screen and (max-width: 767px) {.tg {width: auto !important;}.tg col {width: auto !important;}.tg-wrap {overflow-x: auto;-webkit-overflow-scrolling: touch;margin: auto 0px;}}</style>
<div class="tg-wrap"  style="width:60%"><table class="tg">
<thead>
  <tr>
    <th class="tg-ul38">Detail</th>
    <th class="tg-rz9m">Grade decomposition</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-1wig"> Class project (=hand in ) </td>
    <td class="tg-amwm"> 80% </td>
  </tr>
  <tr>
    <td class="tg-0lax">Data management</td>
    <td class="tg-baqh">15%</td>
  </tr>
  <tr>
    <td class="tg-0lax">Descriptive analysis</td>
    <td class="tg-baqh">15%</td>
  </tr>
  <tr>
    <td class="tg-0lax">Modeling (ML and/or NLP)</td>
    <td class="tg-baqh">15%</td>
  </tr>
  <tr>
    <td class="tg-0lax">Code format (clean code and GitHub)</td>
    <td class="tg-baqh">15%</td>
  </tr>
  <tr>
    <td class="tg-0lax">Oral presentation (individual + group component)</td>
    <td class="tg-baqh">20%</td>
  </tr>
  <tr>
    <td class="tg-1wig"> Project pitch </td>
    <td class="tg-amwm"> 10% </td>
  </tr>
  <tr>
    <td class="tg-1wig"> Active class participation (individual) </td>
    <td class="tg-amwm"> 10% </td>
  </tr>
</tbody>
</table></div></center>


## Course project

### In short
The bulk of the evaluation arises from the course project that students have to hand in . 
This is a computing project to be realized by groups of 2 persons. The content is free, but will have to include:
- The use of several datasets that will be merged and cleaned;
  - Can be collected from the web (scrapping, API) or downloaded from existing databases;
- Descriptive statistics with meaningfull visualisation
- Modelling (ML and/or NLP) with interpretation of the results

Students are invited to propose themes that they care about. 

The project has to use Git and should be made available on Github.

### Project expectations
The project is a problem to which you want to find an answer, using data.

The first step is therefore to look for a problematization and contextualization. You should investigate a subject that appeals to you, so that you can motivate the reader to become involved in your approach.

There are three dimensions to the project. For each of these parts, you can go more or less far. But you should deepen at least one of the three dimensions (ie. the "advanced" bullet points below).

##### 1. Data managagement

The data can be directly available in the form of .txt, .csv files, etc. or come from websites (scrapping, API). 

You are likely to get data that is not 'clean': set up cleaning protocols to get a reliable and robust dataset(s) at the end of this stage to conduct your analysis. This is also the time to create variables that are more understandable, better identified, etc.

##### 2. Descriptive analysis and graphical representations

With descriptive statistics, you seek to have an overall view of the major trends in your data: the link with the problem, how it allows you to answer it, what the first elements of the answer are... Each result must be interpreted (what does it show, how does it validate/contradict your argument?). In terms of graphical representations, several levels are possible. You can simply represent your data using `matplotlib`, go further with `seaborn` or `scikit-plot`. The basis of a good visualization is to find the right type of graph for what you want to show (do you need a scatter or a line to represent an evolution?) and to make it visible: a legend that makes sense, axes with names etc. 

##### 3. Modelling
Last, you will propose a modelling approach to complete / reinforce the descriptive analysis. The model does not matter (linear regression, random forest or other): it must be appropriate (meet your problem) and justified. You can also compare several models that do not have the same purpose.
The results must be interpreted as well.

##### Minimal expectation by part:
Requirements

1. <bcolor>Data retrieval</bcolor>
  - Standard: 
    - Use several data sources, data cleaning
  - Advanced: 
    - Data collection with webscraping
    - Merge several datasets

1. <bcolor>Data visualisation</bcolor> 
  - Standard:
    -  Propose at least 4 exhibits (graphs or tables) 
  - Advanced: 
    - One more elaborated figures, such as maps, or unsupervised learning representations

1. <bcolor>Data modelling</bcolor>
   - Standard:
     - Supervised ML approach: compare at least 2 models
     - or NLP 
  - Advanced: 
    - Both a ML model and some NLP (for example)


### Organisation

#### Hand-in requirement

- A report taking the form of a **Jupyter Notebook** 
  - Exception: if you want to develop an application (`Dash` or `Streamite`)
  - Make sure your notebook is "correctly compiled" (ie. cells named `[1]-[N]`)
  - You might need other python or notebook files in the upstream analysis

- Everything should be hosted on a **Github repository**: data, code, notebook, slides
  - Project folder should be have a well-defined structure
  - Code should be clean. Eg:
    - functions instead of copy paste
  - You must have a `README.md` in the main directory with:
    - Instructions on how we can build the assignment & what it does;
    - It should clearly indicate which file corresponds to the report (or the link to the deployed application).

#### Project pitch
We will discuss your proposed project so that I can evaluate whether it is doable within the time frame. 
We will discuss this together either during the [project kick-off](kick-off.md). In case you cannot attend this session, you should send me an email by April 18th specifying the group members, and detailing the question, the data and the methods that you shall use. 


#### Final presentation
In May, you have to hand in the project and present your project to the instructors. 

The oral should be based on a beamer presentation. The presentation should present the question that you aim at answering, the underlying data, the descriptive and the modelling steps. You will be asked questions regarding the choice of the different visualisation and modelling approaches. 

While the overall grade of the course project is at the group level, the presentation includes an individual dimension. 


#### Submission format
Invite @malkaguillot to collaborate on your GitHub repository by the due date (see [here](https://raw.githubusercontent.com/malkaguillot/ECON2206-Data-Management-2022/main/lectures/images/add-colaborator.png)).


### Some ideas and past projects
- A platform inspired by [bxl-malade](https://bxl-malade.medor.coop/) for Liège using [opendata Liège](https://opendata.liege.be/) et [WalStat](https://walstat.iweps.be/walstat-open-data.php)
- A map of Belgium with communal level information from [WalStat](https://walstat.iweps.be/walstat-open-data.php) for Wallonia, [IBSA](https://ibsa.brussels/) for Bruxelles, and [statistics-flanders](https://www.vlaanderen.be/en/statistics-flanders).
- From past years:
  - Corporate performance and employee sentiment ([github](https://github.com/corentinwerenne/internship-dashboard))
  - Modelling hotel prices in Paris using data from booking
  - Visualisation of the Real Estate Landscape in the Province of Liège using data from Immoweb


## Useful links
- Details on [class evaluation](https://malkaguillot.github.io/ECON2206-Data-Management/docs/utils/class-evaluation/)
