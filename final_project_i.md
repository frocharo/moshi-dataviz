| [Home](https://frocharo.github.io/moshi-dataviz/) | [Assignments](https://frocharo.github.io/moshi-dataviz/assingments.html) | [Challenges](https://frocharo.github.io/moshi-dataviz/challenges.html) | [In class](https://frocharo.github.io/moshi-dataviz/inclass.html) | [Final Project I](https://frocharo.github.io/moshi-dataviz/final_project_i.html)| Final Project II | Final Project III |

# Final Project I

## Outline
How the public transportation can improve the welfare of the people? What if the people could have more time? But where will we get this additional hours?

Setup: In Mexico City I spend 2 hours per journey from my home to my university daily, so like 40 days per year missed in bus and subway.

Conflict: In Mexico City the bad public transportation have been normalized. It's slow, insecure and dirty. So the population spend at least 50 minutes per journey.
This does not look too bad but in comparison with other cities, like Stockholm or Pittsburg, where the average time is not longer than 30 minutes and, if we add the insecurity, commuting in Mexico City is inneficient. 

Resolution: When I went to Stockholm and Pittsburgh this year, I got more time for different activities: workout, volunteering in religious organizations and cultural activities with friends.
I found that a possible set of policy instruments are: defined bus stops, tracking on app and ways free to obstacles. 


### Commuting in three cities
#### Stockholm
#### Pittsburgh
#### Mexico City

### Welfare from commuting


## Initial sketches
<img width="1492" height="978" alt="image" src="https://github.com/user-attachments/assets/8d106f92-74cc-4ccc-8a38-e62b2a1b3c97" />

<div class='tableauPlaceholder' id='viz1790220412999' style='position: relative'><noscript><a href='#'><img alt='At least 50 minutes per journey in Mexico City ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;eo&#47;eod_2017_dataset&#47;barchart2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='eod_2017_dataset&#47;barchart2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;eo&#47;eod_2017_dataset&#47;barchart2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='es-ES' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1790220412999');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


## Data

*Encuesta Origen Destino 2017*, [https://en.www.inegi.org.mx/programas/eod/2017/]([https://en.www.inegi.org.mx/programas/eod/2017/)

It's a survey about time, means of transportation, purpose, expenditure, departure and destination of the mobility in Mexico City, State of Mexico and Hidalgo. I will analyze only the population based in Mexico City who use public transportation (bus, subway and taxi).

*2022 NextGen National Household Travel Survey Core Data*, [http://nhts.ornl.gov](http://nhts.ornl.gov)

It's nationally weighted survey dataset that provides detailed information on who travels, how they travel, why they travel, and how much they travel in the United States. From this survey I will extract the data for Pittsburgh. 

*Resvanor i Sverige 2025*, [https://www.trafa.se/transportmonster/RVU-Sverige/](https://www.trafa.se/transportmonster/RVU-Sverige/)

It's the Sweden's official national travel survey, managed by Trafikanalys. It measures how people travel in their daily lives, including when trips are made, which transport modes are used, and the purpose of each trip. From this survey I will extract the data for Stockholm.

## Method and medium
I already prepared the data from Mexico City and I did the prior sketch. Now I'm preparing the data about Pittsburgh and Stockholm. The last one is the most difficult because there is not dataset, only reports. Fortunately, the available information could be enough for my comparison. I will use R for cleaning, joining and summarizing data, but I'm using Tableu for visualizations. May be I will explore Shorthand for trying to get more dynamic presentation. 


## References
Federal Highway Administration. (2022). *2022 NextGen National Household Travel Survey Core
Data*, U.S. Department of Transportation, Washington, DC. Available online:
[http://nhts.ornl.gov.](http://nhts.ornl.gov.)

Instituto Nacional de Estadística y Geografía (INEGI). *Encuesta Origen Destino 2017*. Available online: 
[https://en.www.inegi.org.mx/programas/eod/2017/](https://en.www.inegi.org.mx/programas/eod/2017/ )

Trafik Analysis. (2025). *Resvanor i Sverige 2025*. Available online: 
[https://www.trafa.se/transportmonster/RVU-Sverige/](https://en.www.inegi.org.mx/programas/eod/2017/ )

## AI Acknowledgments

I recognize that I'm using AI only for getting orientation to use Tableu and R. 
