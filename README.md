### SIADS697_TeamMADScientists
Capstone Project for Team MAD Scientsts

<img src="https://upload.wikimedia.org/wikipedia/en/2/21/Detroit_Public_Schools_logo.svg" alt="Detroit Public Schools Community District" width="200"/> X <img src="https://brand.umich.edu/assets/brand/style-guide/logo-guidelines/U-M_Logo-Hex.png" alt="University of Michigan" width="200"/>

# Socioeconomic Segregation in the Detroit Public Schools Community District (DPSCD)

Welcome to the <strong>Socioecomomic Segregation in the Detroit Public Schools Community District (DPSCD) Project</strong> for the University of Michigan - Master of Applied Data Science program. The authors Sydney Schwartz, Thomas Friss, Robby Waite, and Justin Young formed this capstone team, MAD Scientists, with the intent of exploring data sets comparing the schools within 27 different zip code areas that create DPSCD. The data that was explored includes assessment test score data from the DPSCD open data portal, state and federal per pupil expenditure (PPE), GIS open data on school district boundaries within the state of Michigan and USA census tract areas on median household income. The enormity of the school district and the diversity within it leaves us believing that socioeconomic segregation may be prevalent between the school zip code boundaries in the DPSCD. 

## Data

First phase of this project was identifiying open scource data that would be useful to investigate our story by helpign us comparing the schools within 27 different zip code areas that create DPSCD. We settled on using the following resources in our project:

<li>Test score data from the DPSCD open data portal</li>
<li>State and federal per pupil expenditure (PPE)</li>
<li>GIS open data on school district boundaries within the state of Michigan</li>
<li>USA census tract areas on median household income</li></br>

These data sources should be availavle in perpituity directly from the original sources via an API. All data used within the final deliverable of the project presented here can be found in this github repository and our Google drive[link].

## Method and results

This study encompasses a large amount of data focused on the Detroit Metro Area. With advanced data cleaning and analysis, we were equipped to explore correlations, insights, and statistical evidence on whether or not socioeconomic segregation can be seen between schools, within zip code boundaries. Finding out if segregation exists, we can help parents and students make an informed decision on what schools to go to. Additionally, this information could inform district authorities to help gain a better understanding of what areas, if any, need intervention to stop the continuation of socioeconomic segregation that could have dire effects on the DPSCD.

Our findings resulted in unexpected results. Though the results may suggest DPCSD is making adjustments for the benefit of the total community, rather than feeding into inequality in socioeconomic resources. Our findings did result with effect sizes that were too small to be detected and data not giving us direct insight into the relationships of interest to confirm that DPCSD is making decisions to support the community as best it can. 

## Repository overview

An overview of the directory structure and files:
<pre>
├── Notebooks</br>
├── README.md</br>
├── assets</br>
│   ├── school shapefiles</br>
│   ├── detroit shapediles</br>
│   ├── other data</br>
│   ├── testing data</br>
│   └── saved data</br>
└── research</br>
│   ├── testing dataframe notebook</br>
│   ├── sydney schwartz notebook</br>
│   ├── thomasfriss notebook</br>
│   ├── robby waite notbook</br>
│   └── justin young notebook</br>
├── requirements.txt</br>
└── FINAL_BLOG</br>
</pre>
<li>
<strong>research</strong>
<p>This is where each of the team members explored the data and examined different models.</p>
</li>
<li>
<strong>assets</strong>
<p>The raw data that is used in each of the models.</p>
</li>
<li>
<strong>final notbooks</strong>
<p>The presentation of the results of each of the models and conclusion of the project.</p>
</li>
<li>
<strong>requirements</strong>
<p>This is a list of all of a project's dependencies. This includes the libraries needed and the specific version of each dependency.</p>
</li>

## Running instructions

To and replicate our workflow, simply download the assets folder, our 'Final Blog' file, and requirements.txt file. Upload all into a notebook environment and execute the 'Final Blog' file. Another option can be to simply navigate to this URL: https://deepnote.com/@capstone-team-mad-scientists/MADS-Capstone-Project-e115903d-6f9d-4ba6-a598-8111e36ee3b2 and see our work in a article format. 

## Citations

Broer, M., Bai, Y., Fonseca, F. (2019). <em>Socioeconomic Inequality and Educational Outcomes: An Introduction. In: Socioeconomic Inequality and Educational Outcomes.</em> IEA Research for Education, vol 5. Springer, Cham. https://doi.org/10.1007/978-3-030-11991-1_1</br>

Monarrez, T. (2018, September 17). <em>Do New York City's school attendance boundaries encourage racial and ethnic segregation?</em> Urban Institute. Retrieved June 26, 2022, from https://www.urban.org/urban-wire/do-new-york-citys-school-attendance-boundaries-encourage-racial-and-ethnic-segregation</br>

Owens, A. (2018). <em>Income segregation between school districts and inequality in students ... American Sociological Association.</em> Retrieved June 26, 2022, from https://www.asanet.org/sites/default/files/attach/journals/jan18soefeature.pdf</br>   

Papay JP, Murnane RJ, Willett JB. <em>Income-Based Inequality in Educational Outcomes: Learning From State Longitudinal Data Systems.</em> Educational Evaluation and Policy Analysis. 2015;37(1_suppl):29S-52S. doi:10.3102/0162373715576364</br>

Reardon, S. (2019, May 14). <em>Income inequality affects our children's educational opportunities. Equitable Growth.</em> Retrieved June 26, 2022, from https://equitablegrowth.org/income-inequality-affects-our-childrens-educational-opportunities/ 

## About
#####
We are "Team MAD Scientists" - University of Michigan, School of Information Master of Applied Data Science Students, Class of 2022. This project is our Capstone class final deliverable. 

Team Members:</br>
- Sydney Schwartz</br>
- Thomas Friss</br>
- Robby Waite</br>
- Justin Young</br>
#####

## Any questions?

Feel free to reach out to us:</br>
<strong>Thomas Friss</strong> <code>tfriss [at] umich [dot] edu</code></br>
<strong>Sydney Schwartz</strong> <code>sydneysc [at] umich [dot] edu</code></br>
<strong>Robby Waite</strong> <code>robwaite [at] umich [dot] edu</code></br>
<strong>Justin Young</strong> <code>juyo [at] umich [dot] edu</code></br>

## License

Text and materials are licensed under a Creative Commons CC-BY-NC-SA license. The license allows you to copy, remix and redistribute any of our publicly available materials, under the condition that you attribute the work (details in the license) and do not make profits from it. 

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
