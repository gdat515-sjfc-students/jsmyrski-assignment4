Question:
---------

My fiancee and I are in pursuit of a house to call our own. Because he
works as a Monroe County Probation Officer, we are unable to live
outside of Monroe County. This, along with other requirements (such as 3
bedrooms, 2 bathrooms, a fenced in backyard for our new golden retriever
pup, etc.) restricts our househunting search. An additional requirement
is that we want our neighborhood to be as safe as possible. Looking at
the data from the Division of Criminal Justice Services helps put into
perspective the types and amounts of crimes that happen in each area of
Monroe County. The question that I will be trying to answer is: “Where
in Monroe County is it the safest to live?”. By plotting the data as a
time series, I will also be able to answer the question “Has the number
of crimes increased or decreased over time in Monroe County?”.

Data:
-----

The data I used to answer these questions was found on Data.NY.Gov and
looked at the Monroe County Crime Index. The Division of Criminal
Justice Services (DCJS) collects crime reports from more than 500 New
York State police and sheriffs’ departments. DCJS compiles these reports
as New York’s official crime statistics and submits them to the FBI
under the National Uniform Crime Reporting (UCR) Program. UCR uses
standard offense definitions to count crime in localities across America
regardless of variations in crime laws from state to state. In New York
State, law enforcement agencies use the UCR system to report their
monthly crime totals to DCJS. The UCR reporting system collects
information on seven crimes classified as Index offenses which are most
commonly used to gauge overall crime volume. These include the violent
crimes of murder/non-negligent manslaughter, forcible rape, robbery, and
aggravated assault; and the property crimes of burglary, larceny, and
motor vehicle theft. Police agencies may experience reporting problems
that preclude accurate or complete reporting. The counts represent only
crimes reported to the police but not total crimes that occurred.

Summary:
--------

To answer the questions posed above, I created a plotly scatter plot to
show the data. I also created a bar graph to show the number of violent
crimes compared to property crimes, specifically looking at 2018. It is
clear from the first scatter plot that Rochester City Police Department
has the largest number of crimes compared to all other local Police
Departments. It is clear that the number of crimes for all local Police
Departments have seemed to drop, meaning that overall the towns on
Monroe County are safer now than they were ten years ago. Looking at
just 2018 statistics, the safest town to live in would be Fairport. The
Fairport Police Department reported only 1 violent crime and 23 total
crimes overall in 2018. Compared to Rochester City Police Department who
reported 1,615 violent crimes and 8,651 total crimes overall in 2018.

    ## -- Attaching packages ---------------------------------------------------------------------------------- tidyverse 1.2.1 --

    ## v ggplot2 3.2.0     v purrr   0.3.2
    ## v tibble  2.1.3     v dplyr   0.8.3
    ## v tidyr   0.8.3     v stringr 1.4.0
    ## v readr   1.3.1     v forcats 0.4.0

    ## -- Conflicts ------------------------------------------------------------------------------------- tidyverse_conflicts() --
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

    ## 
    ## Attaching package: 'plotly'

    ## The following object is masked from 'package:ggplot2':
    ## 
    ##     last_plot

    ## The following object is masked from 'package:stats':
    ## 
    ##     filter

    ## The following object is masked from 'package:graphics':
    ## 
    ##     layout

    ## No trace type specified:
    ##   Based on info supplied, a 'scatter' trace seems appropriate.
    ##   Read more about this trace type -> https://plot.ly/r/reference/#scatter
    ## No trace type specified:
    ##   Based on info supplied, a 'scatter' trace seems appropriate.
    ##   Read more about this trace type -> https://plot.ly/r/reference/#scatter
    ## No trace type specified:
    ##   Based on info supplied, a 'scatter' trace seems appropriate.
    ##   Read more about this trace type -> https://plot.ly/r/reference/#scatter
    ## No trace type specified:
    ##   Based on info supplied, a 'scatter' trace seems appropriate.
    ##   Read more about this trace type -> https://plot.ly/r/reference/#scatter
    ## No trace type specified:
    ##   Based on info supplied, a 'scatter' trace seems appropriate.
    ##   Read more about this trace type -> https://plot.ly/r/reference/#scatter
    ## No trace type specified:
    ##   Based on info supplied, a 'scatter' trace seems appropriate.
    ##   Read more about this trace type -> https://plot.ly/r/reference/#scatter
    ## No trace type specified:
    ##   Based on info supplied, a 'scatter' trace seems appropriate.
    ##   Read more about this trace type -> https://plot.ly/r/reference/#scatter
    ## No trace type specified:
    ##   Based on info supplied, a 'scatter' trace seems appropriate.
    ##   Read more about this trace type -> https://plot.ly/r/reference/#scatter
    ## No trace type specified:
    ##   Based on info supplied, a 'scatter' trace seems appropriate.
    ##   Read more about this trace type -> https://plot.ly/r/reference/#scatter
    ## No trace type specified:
    ##   Based on info supplied, a 'scatter' trace seems appropriate.
    ##   Read more about this trace type -> https://plot.ly/r/reference/#scatter

<!--html_preserve-->

<script type="application/json" data-for="htmlwidget-411a29171b7b0d36c7c7">{"x":{"visdat":{"292c7e2a3fca":["function () ","plotlyVisDat"]},"cur_data":"292c7e2a3fca","attrs":{"292c7e2a3fca":{"x":{},"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"y":{},"name":"Brighton","mode":"lines+markers","inherit":true},"292c7e2a3fca.1":{"x":{},"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"y":{},"name":"Brockport","mode":"lines+markers","inherit":true},"292c7e2a3fca.2":{"x":{},"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"y":{},"name":"East Rochester","mode":"lines+markers","inherit":true},"292c7e2a3fca.3":{"x":{},"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"y":{},"name":"Fairport","mode":"lines+markers","inherit":true},"292c7e2a3fca.4":{"x":{},"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"y":{},"name":"Gates","mode":"lines+markers","inherit":true},"292c7e2a3fca.5":{"x":{},"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"y":{},"name":"Greece","mode":"lines+markers","inherit":true},"292c7e2a3fca.6":{"x":{},"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"y":{},"name":"Irondequoit","mode":"lines+markers","inherit":true},"292c7e2a3fca.7":{"x":{},"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"y":{},"name":"Ogden","mode":"lines+markers","inherit":true},"292c7e2a3fca.8":{"x":{},"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"y":{},"name":"Rochester","mode":"lines+markers","inherit":true},"292c7e2a3fca.9":{"x":{},"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"y":{},"name":"Webster","mode":"lines+markers","inherit":true}},"layout":{"margin":{"b":40,"l":60,"t":25,"r":10},"xaxis":{"domain":[0,1],"automargin":true,"title":"Years"},"yaxis":{"domain":[0,1],"automargin":true,"title":"Number of Crimes"},"showlegend":true,"title":"Number of Crimes Reported to Police in Monroe County (1990 to 2018)","hovermode":"closest"},"source":"A","config":{"showSendToCloud":false},"data":[{"x":[2018,2017,2016,2015,2014,2013,2012,2011,2010,2009,2008,2007,2006,2005,2004,2003,2002,2001,2000,1999,1998,1997,1996,1995,1994,1993,1992,1991,1990],"y":[645,808,825,801,879,822,962,989,1097,1247,1019,999,1085,1069,1108,986,1032,1130,1155,858,1056,1234,1189,1236,1151,1074,1173,1307,1123],"name":"Brighton","mode":"lines+markers","type":"scatter","marker":{"color":"rgba(31,119,180,1)","line":{"color":"rgba(31,119,180,1)"}},"error_y":{"color":"rgba(31,119,180,1)"},"error_x":{"color":"rgba(31,119,180,1)"},"line":{"color":"rgba(31,119,180,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":[2018,2017,2016,2015,2014,2013,2012,2011,2010,2009,2008,2007,2006,2005,2004,2003,2002,2001,2000,1999,1998,1997,1996,1995,1994,1993,1992,1991,1990],"y":[97,107,131,159,138,190,156,169,200,189,209,197,177,158,183,258,229,265,274,263,276,263,261,243,350,246,280,287,252],"name":"Brockport","mode":"lines+markers","type":"scatter","marker":{"color":"rgba(255,127,14,1)","line":{"color":"rgba(255,127,14,1)"}},"error_y":{"color":"rgba(255,127,14,1)"},"error_x":{"color":"rgba(255,127,14,1)"},"line":{"color":"rgba(255,127,14,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":[2018,2017,2016,2015,2014,2013,2012,2011,2010,2009,2008,2007,2006,2005,2004,2003,2002,2001,2000,1999,1998,1997,1996,1995,1994,1993,1992,1991,1990],"y":[107,92,126,120,86,133,136,151,140,144,197,151,154,172,159,183,202,214,209,252,319,303,409,371,312,304,260,244,254],"name":"East Rochester","mode":"lines+markers","type":"scatter","marker":{"color":"rgba(44,160,44,1)","line":{"color":"rgba(44,160,44,1)"}},"error_y":{"color":"rgba(44,160,44,1)"},"error_x":{"color":"rgba(44,160,44,1)"},"line":{"color":"rgba(44,160,44,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":[2018,2017,2016,2015,2014,2013,2012,2011,2010,2009,2008,2007,2006,2005,2004,2003,2002,2001,2000,1999,1998,1997,1996,1995,1994,1993,1992,1991,1990],"y":[23,49,51,37,52,58,42,67,41,65,65,60,67,59,88,74,71,76,70,107,90,122,138,166,161,157,140,203,143],"name":"Fairport","mode":"lines+markers","type":"scatter","marker":{"color":"rgba(214,39,40,1)","line":{"color":"rgba(214,39,40,1)"}},"error_y":{"color":"rgba(214,39,40,1)"},"error_x":{"color":"rgba(214,39,40,1)"},"line":{"color":"rgba(214,39,40,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":[2018,2017,2016,2015,2014,2013,2012,2011,2010,2009,2008,2007,2006,2005,2004,2003,2002,2001,2000,1999,1998,1997,1996,1995,1994,1993,1992,1991,1990],"y":[879,901,988,1037,1096,1108,1301,1213,983,1160,1001,1122,1113,1103,1186,1250,1172,1118,1187,1294,1164,1168,1262,1107,1019,1151,1256,1266,1302],"name":"Gates","mode":"lines+markers","type":"scatter","marker":{"color":"rgba(148,103,189,1)","line":{"color":"rgba(148,103,189,1)"}},"error_y":{"color":"rgba(148,103,189,1)"},"error_x":{"color":"rgba(148,103,189,1)"},"line":{"color":"rgba(148,103,189,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":[2018,2017,2016,2015,2014,2013,2012,2011,2010,2009,2008,2007,2006,2005,2004,2003,2002,2001,2000,1999,1998,1997,1996,1995,1994,1993,1992,1991,1990],"y":[2229,2110,2299,2613,2577,2457,2682,2680,2670,2710,2426,2272,2419,2055,2420,2370,2404,2432,2700,2617,2852,3106,3123,3110,2863,2980,2726,2458,2757],"name":"Greece","mode":"lines+markers","type":"scatter","marker":{"color":"rgba(140,86,75,1)","line":{"color":"rgba(140,86,75,1)"}},"error_y":{"color":"rgba(140,86,75,1)"},"error_x":{"color":"rgba(140,86,75,1)"},"line":{"color":"rgba(140,86,75,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":[2018,2017,2016,2015,2014,2013,2012,2011,2010,2009,2008,2007,2006,2005,2004,2003,2002,2001,2000,1999,1998,1997,1996,1995,1994,1993,1992,1991,1990],"y":[1013,1231,903,1447,1487,1447,1710,1621,1574,1593,1471,1648,1711,1837,2062,2151,2294,2321,2566,2311,2548,2695,2709,3115,2537,3120,3242,3204,2834],"name":"Irondequoit","mode":"lines+markers","type":"scatter","marker":{"color":"rgba(227,119,194,1)","line":{"color":"rgba(227,119,194,1)"}},"error_y":{"color":"rgba(227,119,194,1)"},"error_x":{"color":"rgba(227,119,194,1)"},"line":{"color":"rgba(227,119,194,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":[2018,2017,2016,2015,2014,2013,2012,2011,2010,2009,2008,2007,2006,2005,2004,2003,2002,2001,2000,1999,1998,1997,1996,1995,1994,1993,1992,1991,1990],"y":[203,223,292,209,258,225,241,269,396,368,273,233,366,348,336,406,390,368,415,493,493,421,392,390,318,341,391,394,336],"name":"Ogden","mode":"lines+markers","type":"scatter","marker":{"color":"rgba(127,127,127,1)","line":{"color":"rgba(127,127,127,1)"}},"error_y":{"color":"rgba(127,127,127,1)"},"error_x":{"color":"rgba(127,127,127,1)"},"line":{"color":"rgba(127,127,127,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":[2018,2017,2016,2015,2014,2013,2012,2011,2010,2009,2008,2007,2006,2005,2004,2003,2002,2001,2000,1999,1998,1997,1996,1995,1994,1993,1992,1991,1990],"y":[8651,9807,9658,10107,10546,12160,13361,13988,14212,13155,13432,13627,15665,16017,17240,17742,16911,16114,17064,16100,18713,19885,20901,22722,22586,25521,27487,26032,25570],"name":"Rochester","mode":"lines+markers","type":"scatter","marker":{"color":"rgba(188,189,34,1)","line":{"color":"rgba(188,189,34,1)"}},"error_y":{"color":"rgba(188,189,34,1)"},"error_x":{"color":"rgba(188,189,34,1)"},"line":{"color":"rgba(188,189,34,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":[2018,2017,2016,2015,2014,2013,2012,2011,2010,2009,2008,2007,2006,2005,2004,2003,2002,2001,2000,1999,1998,1997,1996,1995,1994,1993,1992,1991,1990],"y":[396,443,470,528,519,491,495,482,551,587,591,622,646,581,605,628,584,656,657,685,793,854,733,793,829,869,823,1023,704],"name":"Webster","mode":"lines+markers","type":"scatter","marker":{"color":"rgba(23,190,207,1)","line":{"color":"rgba(23,190,207,1)"}},"error_y":{"color":"rgba(23,190,207,1)"},"error_x":{"color":"rgba(23,190,207,1)"},"line":{"color":"rgba(23,190,207,1)"},"xaxis":"x","yaxis":"y","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>
<!--/html_preserve-->

    ## No trace type specified:
    ##   Based on info supplied, a 'bar' trace seems appropriate.
    ##   Read more about this trace type -> https://plot.ly/r/reference/#bar
    ## No trace type specified:
    ##   Based on info supplied, a 'bar' trace seems appropriate.
    ##   Read more about this trace type -> https://plot.ly/r/reference/#bar

<!--html_preserve-->

<script type="application/json" data-for="htmlwidget-3ba0725e741b5421ae9a">{"x":{"visdat":{"292c20e42019":["function () ","plotlyVisDat"]},"cur_data":"292c20e42019","attrs":{"292c20e42019":{"x":{},"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"y":{},"name":"Violent Crimes","color":"purple","inherit":true},"292c20e42019.1":{"x":{},"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"y":{},"name":"Property Crimes","color":"yellow","inherit":true}},"layout":{"margin":{"b":40,"l":60,"t":25,"r":10},"xaxis":{"domain":[0,1],"automargin":true,"title":"Police Departments","type":"category","categoryorder":"array","categoryarray":["Brighton Town PD","Brockport Vg PD","East Rochester Vg PD","Fairport Vg PD","Gates Town PD","Greece Town PD","Irondequoit Town PD","Monroe County Park PD","Monroe County Sheriff","Monroe County State Police","Ogden Town PD","Rochester City PD","Webster Town and Vg PD"]},"yaxis":{"domain":[0,1],"automargin":true,"title":"Number of Crimes"},"showlegend":true,"title":"Number of Crimes Reported to Police in Monroe County by Town in 2018","hovermode":"closest"},"source":"A","config":{"showSendToCloud":false},"data":[{"x":["Brighton Town PD","Brockport Vg PD","East Rochester Vg PD","Fairport Vg PD","Gates Town PD","Greece Town PD","Irondequoit Town PD","Monroe County Park PD","Monroe County Sheriff","Monroe County State Police","Ogden Town PD","Rochester City PD","Webster Town and Vg PD"],"y":[32,14,11,1,56,189,91,0,186,26,8,1615,35],"name":"Violent Crimes","type":"bar","marker":{"color":"rgba(102,194,165,1)","line":{"color":"rgba(102,194,165,1)"}},"textfont":{"color":"rgba(102,194,165,1)"},"error_y":{"color":"rgba(102,194,165,1)"},"error_x":{"color":"rgba(102,194,165,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":["Brighton Town PD","Brockport Vg PD","East Rochester Vg PD","Fairport Vg PD","Gates Town PD","Greece Town PD","Irondequoit Town PD","Monroe County Park PD","Monroe County Sheriff","Monroe County State Police","Ogden Town PD","Rochester City PD","Webster Town and Vg PD"],"y":[613,83,96,22,823,2040,922,4,2224,73,195,7036,361],"name":"Property Crimes","type":"bar","marker":{"color":"rgba(141,160,203,1)","line":{"color":"rgba(141,160,203,1)"}},"textfont":{"color":"rgba(141,160,203,1)"},"error_y":{"color":"rgba(141,160,203,1)"},"error_x":{"color":"rgba(141,160,203,1)"},"xaxis":"x","yaxis":"y","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>
<!--/html_preserve-->

Limitations:
------------

The biggest limitation I had with this data was that it didn’t provide
population statistics per year, so I was unable to create a crime rate
and conclude which area was the safest, comparetively speaking. Another
problem I noticed was that there was no “Penfield” or other smaller
towns in the data. I can assume these small towns use the closest large
towns police departments. It was also hard to clarify the boarders of
where these crimes actually occured, since there was no real location
statistics.
