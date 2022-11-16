## Step One: my visualization
My chart is the survey based on registered voters. Share of respondents who said each issue is somewhat between May and August in 2022.

## Sketch out a solution
After critiquing my data visulization, I did the sketch.
For the sketch, since I think the graph lacks the perceptibility and intuitiveness, I hope to reduce the overlapping of each issue, and make each issue clearly displayed in the chart to make the audience read the information with less effort. To achieve that, I modify the chart using the vertical line to display the number change from March to May. Then to show the change trend, I use an arrow and different colors to illustrate that information. The green arrow means the downward trend, while the blue line represents the upward trend, the dot means the same. By highlighting the different trends, the audience can more easily understand different trends of each issue.

## Test the solution
I interviewed two people and they give me following suggestions. 
-Female,20s:
I think the chart’s audience might be the election campaign. I feel the number represents the change of people in addressing each issue. But I’m confused about what each number represents, whether it’s the number of responses or the percentage of people.  And what’s the time period in conducting the survey, whether it’s the change of a year or a month. I basically understand the whole information, but I think it lacks the label and clear annotation to conduct the further illustration. 

-Male,20s:
I understand what this graph means after knowing the time period conducted in the survey and the audience. I think the chart is clear in describing different issues’ change trends, but it may not highlight the information the survey wants to convey. Since I still can’t notify the most important issue and what issue changes most. The combination of color and arrow is a little confusing and distracting. It will be better if you can align the symbol and color. 

## Build my solution
-Original Version:

![Image of Latino Voters](https://www.pewresearch.org/race-ethnicity/wp-content/uploads/sites/18/2022/09/PRE_2022.09.29_NSL-politics_00-05.png)

After collecting the feedback, I found out the interviewers to know the time period and the meaning of each number since I didn’t clear mark and make annotations. The lack of completeness means I need to add the clear headline and label to show the full information. Another common comment is that they think even though the different label and color make it easily illustrate the information, but it may lack the aesthetics since the arrow and color make it chaotic. They also suggest that it will be better to sort each issue according to consistent rules.
After combining interviewers’ suggestions and my thoughts, I did the following modifications to make the graph more clear and aesthetically pleasing.
1. My original chart is hard to implement in the software, therefore I use the scatter plots to make the graph. I used the line to connect each spot so the audience can easily know the changing trend.
2. I added the clear title and legend to clarify the information I want to convey to the audience, including the detailed headline and legend to show the basic information about the survey
3. To reduce the overlapping information and reduce efforts made by the audience to identify the trend, I let each issue take separate room to show their trend
4. To make the audience know the overall trend, I sorted out each issues’ trend according to three dimensions(increase,same,decrease). And I move the same category near to each other.
5. For the information I want to highlight, I also used different colors to highlight the most important issue, the largest increase and decrease issues. So the audience can catch the most important information.

<div class='tableauPlaceholder' id='viz1668615235770' style='position: relative'><noscript><a href='#'><img alt='Abortion rises as an election issue for Latino registered voters(survey conducted between 2022 May-August) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ch&#47;chart_16686132236580&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='chart_16686132236580&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ch&#47;chart_16686132236580&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1668615235770');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
