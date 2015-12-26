---
title       : Venezuelan Educational System 
subtitle    : App to predict probability of being part of desertion in high school
author      : Sonia Marin
job         : Create Data Products - Course Project
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz]  
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
ext_widgets : {rCharts: [libraries/nvd3]}
---

## Objective
An App was created to calculate the probability of being part of desertion in high school according to the statistic of the INE (National Institute of Statistic in Venezuela since 2002-2012).   

In this presentation you will see some motivational issues and statistics about
desertions in high school in the Venezuelan Educational System.   


---

## Introduction
1. In Venezuela 42% of the population with age between 15 and 29 years old go to school.   

2. The school asistence is slightly higher for women than for men.   

3. The average age when half of the young students left school is about 17.4 years old.   


### Motivation  

This App try to call the attention of parents and young people about the high rates of desertion and how far or close can be any young men or women of being part of statistics.   

So, are you a parent? or a young men or women? Do you know what is the probability of being part of the population that leave high school?   

--- 

## Desertions by student current year of studying from 2003-2012
### Current year of stuying refers to:
#### 1= First year 2= Second year 3= Third year 4= Fourth year





<div id = 'chart3' class = 'rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawchart3()
    });
    function drawchart3(){  
      var opts = {
 "dom": "chart3",
"width":    800,
"height":    400,
"x": "scholar",
"y": "freq",
"group": "year",
"type": "multiBarChart",
"id": "chart3" 
},
        data = [
 {
 "item": 1,
"scholar": "2002/03",
"freq": 86119,
"year": 1 
},
{
 "item": 2,
"scholar": "2002/03",
"freq": 39913,
"year": 2 
},
{
 "item": 3,
"scholar": "2002/03",
"freq": 27084,
"year": 3 
},
{
 "item": 4,
"scholar": "2002/03",
"freq": 24104,
"year": 4 
},
{
 "item": 5,
"scholar": "2003/04",
"freq": 81902,
"year": 1 
},
{
 "item": 6,
"scholar": "2003/04",
"freq": 39294,
"year": 2 
},
{
 "item": 7,
"scholar": "2003/04",
"freq": 26040,
"year": 3 
},
{
 "item": 8,
"scholar": "2003/04",
"freq": 36167,
"year": 4 
},
{
 "item": 9,
"scholar": "2004/05",
"freq": 72302,
"year": 1 
},
{
 "item": 10,
"scholar": "2004/05",
"freq": 38196,
"year": 2 
},
{
 "item": 11,
"scholar": "2004/05",
"freq": 26007,
"year": 3 
},
{
 "item": 12,
"scholar": "2004/05",
"freq": 35375,
"year": 4 
},
{
 "item": 13,
"scholar": "2005/06",
"freq": 65212,
"year": 1 
},
{
 "item": 14,
"scholar": "2005/06",
"freq": 37452,
"year": 2 
},
{
 "item": 15,
"scholar": "2005/06",
"freq": 25536,
"year": 3 
},
{
 "item": 16,
"scholar": "2005/06",
"freq": 35231,
"year": 4 
},
{
 "item": 17,
"scholar": "2006/07",
"freq": 58992,
"year": 1 
},
{
 "item": 18,
"scholar": "2006/07",
"freq": 36176,
"year": 2 
},
{
 "item": 19,
"scholar": "2006/07",
"freq": 30511,
"year": 3 
},
{
 "item": 20,
"scholar": "2006/07",
"freq": 31919,
"year": 4 
},
{
 "item": 21,
"scholar": "2007/08",
"freq": 49551,
"year": 1 
},
{
 "item": 22,
"scholar": "2007/08",
"freq": 37295,
"year": 2 
},
{
 "item": 23,
"scholar": "2007/08",
"freq": 31307,
"year": 3 
},
{
 "item": 24,
"scholar": "2007/08",
"freq": 34539,
"year": 4 
},
{
 "item": 25,
"scholar": "2008/09",
"freq": 54108,
"year": 1 
},
{
 "item": 26,
"scholar": "2008/09",
"freq": 33383,
"year": 2 
},
{
 "item": 27,
"scholar": "2008/09",
"freq": 37549,
"year": 3 
},
{
 "item": 28,
"scholar": "2008/09",
"freq": 44161,
"year": 4 
},
{
 "item": 29,
"scholar": "2009/10",
"freq": 55618,
"year": 1 
},
{
 "item": 30,
"scholar": "2009/10",
"freq": 26807,
"year": 2 
},
{
 "item": 31,
"scholar": "2009/10",
"freq": 27567,
"year": 3 
},
{
 "item": 32,
"scholar": "2009/10",
"freq": 28721,
"year": 4 
},
{
 "item": 33,
"scholar": "2010/11",
"freq": 55118,
"year": 1 
},
{
 "item": 34,
"scholar": "2010/11",
"freq": 20312,
"year": 2 
},
{
 "item": 35,
"scholar": "2010/11",
"freq": 16869,
"year": 3 
},
{
 "item": 36,
"scholar": "2010/11",
"freq": 20647,
"year": 4 
},
{
 "item": 37,
"scholar": "2011/12",
"freq": 70076,
"year": 1 
},
{
 "item": 38,
"scholar": "2011/12",
"freq": 26770,
"year": 2 
},
{
 "item": 39,
"scholar": "2011/12",
"freq": 27896,
"year": 3 
},
{
 "item": 40,
"scholar": "2011/12",
"freq": 27256,
"year": 4 
} 
]
  
      if(!(opts.type==="pieChart" || opts.type==="sparklinePlus" || opts.type==="bulletChart")) {
        var data = d3.nest()
          .key(function(d){
            //return opts.group === undefined ? 'main' : d[opts.group]
            //instead of main would think a better default is opts.x
            return opts.group === undefined ? opts.y : d[opts.group];
          })
          .entries(data);
      }
      
      if (opts.disabled != undefined){
        data.map(function(d, i){
          d.disabled = opts.disabled[i]
        })
      }
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .width(opts.width)
          .height(opts.height)
          
        if (opts.type != "bulletChart"){
          chart
            .x(function(d) { return d[opts.x] })
            .y(function(d) { return d[opts.y] })
        }
          
         
        
          
        

        
        
        
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
    };
</script>

---

## References
 1. http://www.ine.gov.ve/index.php?option=com_content&view=category&id=64&Itemid=39
 2. http://www.ine.gov.ve/index.php?option=com_content&view=category&id=98&Itemid=51
 3. UCAB. Proyecto Juventud Encuesta Nacional de Juventud 2013 - IIES
 
 4. http://slidify.github.io/dcmeetup/demos/interactive/
 


