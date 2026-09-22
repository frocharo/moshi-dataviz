# Assignments

### OECD
#### 1) OECD countries have more public debt (linear)
[<img width="1491" height="826" alt="image" src="https://github.com/user-attachments/assets/122ea162-c790-4de2-987a-62cdbb861cad" />](https://public.tableau.com/views/TableuA1/Sheet1?:language=es-ES&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

#### 2) OECD countries have more public debt (table)
[<img width="1659" height="811" alt="image" src="https://github.com/user-attachments/assets/8ea2cf85-dd15-4046-b8c1-6c5bef92d89d" />](https://public.tableau.com/views/TableuA1OECDTable/Sheet3?:language=es-ES&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

#### 3) OECD countries have more public debt than GDP (bubbles)
[<img width="666" height="707" alt="image" src="https://github.com/user-attachments/assets/c4e4a72b-dacf-461e-a2bf-65fb6a80eed0" />
](https://public.tableau.com/shared/TQ5XJ7K4J?:display_count=n&:origin=viz_share_link)

### Makeover Monday

**Original dataviz**

<img width="987" height="834" alt="image" src="https://github.com/user-attachments/assets/d2e124a9-7cac-4b7e-b31c-b12e88ec5fef" />             

[Click here](https://public.tableau.com/views/MOM2026W29-USDataCenterLocations/MOM2026W29-USDataCenterLocations?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) to visualize the whole dataviz.

I chose this visualizations because I saw a lot information on it, so I was impressed because the flux between the US map and the bar chart. Additionally, I'm interested on data centers so I think that with the location, status and electricity consumption I could make a dataviz for some environmental message. Also I chose this map because I reviewed its dataset and it contains a lot of variables and observations, then I believed that I can get a great final product.

*Prep*

I started analyzing the original map. I said on Forms that it didn't used very well the spatial features of each state. Then I looked how to take advantage of the information per state but without over visualizing information like in the original one. Due this is a map and not a chart, I needed to learn more about how to handle it on Tableu, so I took a course on DataCamp provided by my home university. My preparation, as you can see, was not like in the book: find a quite space, be focused and gather your data. First I needed to understand the pros & cons from the original dataviz, after I got training for Tableu and finally I started thinking in how to sketch a first draft. 

I decided to speak to an audience concerned by the increasing amount of data centers in US. I would like to trigger a feeling of urgency and risk, so my dataviz is data-driven but also declarative. I wanted to keep in mind: "Data centers are everywhere, every time they are more and they are wasting our resources". 

*Sketch*

My first draft was focused on electricity consumption, however the dataset is not accurate in this matter. More than 50% of the observations have not information about the electricity consumption, and the others have different data in different measures. So I ruled out this approach because I'm not quite sure about the completeness and truthfulness of the information.

<img width="1319" height="727" alt="image" src="https://github.com/user-attachments/assets/00e2589b-a51b-4cfe-8294-379d0140a772" />

The second draft was focused on the amount of data centers. I looked a represented like a terrible sun over US, but I would miss the spatial features. Also may be is not very intuitive. The I discarded it too. 

<img width="1314" height="895" alt="image" src="https://github.com/user-attachments/assets/595f7403-3e0a-4458-b592-6e36e4cc278f" />

The third draft was mix map for representing the total amount and status of data centers ("the terrible sun") and the amount per state in each US state.

<img width="996" height="735" alt="image" src="https://github.com/user-attachments/assets/acd16ec3-851b-4509-9be1-6364707ffe62" />

I liked so I moved on. 

*Test*

Testing my map was very useful because I received good feedback from my classmates. I created a simple Google Forms in order to record and summarize their ideas. The results were the following:

<img width="755" height="614" alt="image" src="https://github.com/user-attachments/assets/34be2500-3178-4711-8c5c-21a855d79f41" />
<img width="756" height="837" alt="image" src="https://github.com/user-attachments/assets/6956d0c3-ccdb-4958-8582-c54440d87bdb" />

During the conversations they remarked their liking for the map and confusing for the bubbles. I showed the original dataviz and they make understand that the advantage of my proposal was the simplicity instead a presentation with a lot of information. Then I think that may be using only the map I can achieve the perceptibility and intuitiveness. Also they said on Forms their engagement with the topic after my dataviz. 

**My final dataviz**

<div class='tableauPlaceholder' id='viz1790110841557' style='position: relative'><noscript><a href='#'><img alt='Data centers are everywhere ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;Datacentersareeverywhere&#47;sketch1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Datacentersareeverywhere&#47;sketch1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;Datacentersareeverywhere&#47;sketch1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='es-ES' /></object></div>               
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1790110841557');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

My only concern with my final product is its the interactivity. It's an advantage because it allow me to deploy more information when you select a state but it could be a disadvantage if the map is only printed because you could miss the access to the status data per state. 
