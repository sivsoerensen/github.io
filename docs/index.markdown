---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# TO RUN LOCALLY WITHOUT COMMITTING AND SEE WEBSITE:
# (base) sivs@DTU-5CG125923N:~/socialViz/github.io/docs$ bundle exec jekyll serve
# website: http://127.0.0.1:4000/week7/

layout: default
---

{% include_relative _content/example.md %}

Write text here.. 

First plot:
<img src="../assets/png/focuscrime_occurences_barplot.png" 
    width="100%" 
    height="100%">

Second plot:
<iframe src="/assets/html/HeatMapWithTime_prostitution.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="600"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

Third plot:
<iframe src="/assets/html/focuscrime_frequency_interactive_piechart.html" 
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="600"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>