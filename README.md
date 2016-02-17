## Summary


This projects creates two visualizations to show how Systolic Blood Pressure (SBP) and Gross Domestic Product (GDP) are
correlated in a time series. 


## Motivation

Curious about economy and health indices of countries.

## Design

Utilized dimple.js to show an animated version of data compiled from Gapmider.

The first graph shows a sample of seven countries where opposite trends are observed.
Bubble chart was chosed where each dot correspond to a (GDP, SBP). Colors distinguished
countries and all years from the series are displayed.

To generalize this find, I needed one measure that summarizes the correlation for every 
country, and therefore chose Pearson's r. I decided to use bar charts in a form 
of histogram, where each bar correspond to the counts in the bin. 


## Feedback

Feedback was on making the graph more friendly to an audience not familiar with statistical terms.
In addition, I received comments about the interpretability of the animation. As a result, I decided 
to simplify the animation. Now, its users' choice which countries to compare and all years are
displayed simultaneously.
The histogram, before a static image, now is coded in dimple, where dimple now tells the counts
in each correlation bin and per GDP group. 
To avoid confusion if the bars are stacked on top of each other or in front of each other, a space was added
and the bins were individually labelled. Finally, a wikipedia link to Pearson's r and an explanation
was added to the supporting text.

## Resources

R, Python, dimple.js
