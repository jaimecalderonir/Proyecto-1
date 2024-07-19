<h1>Longevity and nutrition</h1>
<h2>Authors</h2>
<ul>
    <li>Jaime Calderón <a href=https://github.com/jaimecalderonir/> href=https://github.com/jaimecalderonir/</a></li>
    <li>Nuria García <a href=https://github.com/Nunurix/> https://github.com/Nunurix/</a></li>
    <li>Rodrigo Ortíz <a href=https://github.com/Nunurix/> https://github.com/Rodriortiz1/</a></li>
</ul>
<h2>Introduction</h2>
<p>This project is part of the Ironhack boothcamp <a href=https://www.ironhack.com/> https://www.ironhack.com/ </a>. We want to explain the relationship between food supply, life expectancy and obesity. </p>
<p>In this repository, you will find, in total, four documents:</p>
    <ul>
        <li>Python code</li>
        <li>PDF presentation</li>
        <li>This document</li>
    </ul></p>
<h2>Origin of the data</h2> 
    <p>
        The information we have worked with comes from two sources:
    </p>
    <ul>
        <li>
            On the one hand, we have looked at <a href="https://datosmacro.expansion.com/demografia/esperanza-vida/" target="_blank">La Expansión</a> on global life expectancy.
        </li>
        <li>
            We have also used data from the <a href="https://www.fao.org/faostat/es/#data/FBS" target="_blank">FAO (Food and Agriculture Organisation of the United Nations)</a>.
        </li>
    </ul>

<h2>Starting questions</h2>
<p>
        The questions we want to address in this study are the following:
    </p>
    <ul>
        <li>Which food groups are the most consumed by each continent?</li>
        <li> Which continents supply the most alcoholic beverages and sugars?</li>
        <li> Which continent has the longest life expectancy? </li>
        <li>Is there a direct relationship between obesity and all these factors?</li>
    </ul>
<h2>Methodology</h2>
    <p>First of all, we have proceeded to conceptualize our research, in order to proceed with the search for and collection of data.</p>
    <p> Specifically, we will work with the following data:
        <ul>
            <li>Food supply by country (2016-2021)</li>
            <li>Obesity rate by country (2016-2021)</li>
            <li>Life expectancy rate by country (2016-2021)</li>
            <li>Mortality rate by country (2016-2021)</li>
        </ul>
    <p>We have used two different techniques to obtain these data: CSV and Web Scraping in different sources of information.</p>
    <p>The next step was to clean the data in order to have a single dataframe with all the information. This cleaning process involved the following steps:</p>
    <ul>
        <li>Clearing of Nan and duplicates.</li>
        <li>Deletion of columns and renaming.</li>
        <li>Union of the different dataframes coming from the use of CSV and Web Scraping.</li>
        <li>Creating Pivot Tables.</li>
    </ul>
    <p>Finally, we have worked on the visualisation of the data in order to be able to draw conclusions by operating with the data obtained. For the creation of the graphs that can be seen in the presentation we have used "Matplotlib" and "Seaborn".</p>
<h2>Conclusions</h2>
    <p>Although we have found certain relationships between diet and longevity, everything seems to indicate that it is necessary to study what other factors contribute to improving or worsening life   expectancy between continents, beyond diet.</p>
<p>Although we can see that diet is related to obesity, we believe that we could go deeper to be more conclusive about this relationship.</p>
<h2>Links</h2> 
     <ul>
        <li><a href=https://trello.com/invite/b/66976d5803fa1faf6220bcfa/ATTId2ade52c225ce3bedd220af20fd9a746E4B839FB/longevidad-y-alimentacion> Trello</a></li>
    </ul>
