---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# TO RUN LOCALLY WITHOUT COMMITTING AND SEE WEBSITE:
# (base) sivs@DTU-5CG125923N:~/socialViz/github.io/docs$ bundle exec jekyll serve
# website: http://127.0.0.1:4000/week7/

# {% include_relative _content/example.md %}

layout: default
---



Write text here.. 

First plot:

#![image](/assets/png/focuscrime_occurences_barplot.png){: 
#style="float: center; margin: 0 2rem 0 0;" width="100%" }


First plot:
<img src="https://sivsoerensen.github.io/week7/docs/assets/png/focuscrime_occurences_barplot.png" 
    width="100%" 
    height="100%">



Second plot:
<iframe src="https://sivsoerensen.github.io/docs/assets/html/HeatMapWithTime_prostitution.html"
    width="100%"
    height="600">
</iframe>

Third plot:
<iframe src="docs/focuscrime_frequency_interactive_piechart.html" 
    width="100%"
    height="600">
</iframe>

{% include focuscrime_frequency_interactive_piechart.html url="https://sivsoerensen.github.io/week7/docs/focuscrime_frequency_interactive_piechart.html" %}


{% include HeatMapWithTime_prostitution.html url="https://github.com/sivsoerensen/week7/blob/main/docs/_includes/html/focuscrime_frequency_interactive_piechart.html" %}

