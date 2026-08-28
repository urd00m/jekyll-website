---
layout: page
title: Research
---

<center>
<i class="fa fa-android fa-5x" style="color: #000000;"></i>&nbsp;&nbsp;&nbsp; 
<i class="fa fa-mobile fa-5x" style="color: #000000;"></i>&nbsp;&nbsp;&nbsp; 
<i class="fa fa-desktop fa-5x" style="color: #000000;"></i>&nbsp;&nbsp;&nbsp; 
<i class="fa fa-eye fa-5x" style="color: #000000;"></i>&nbsp;&nbsp;&nbsp; 
<i class="fa fa-lock fa-5x" style="color: #000000;"></i>
</center>

<!-- ![research photo](/assets/images/research.jpg){:style="display:block; margin-left:auto; margin-right:auto"} -->
<!-- : width="300" -->

# Research Interests 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;My research interests lie in hardware/systems security with a side on computer systems. 
Recently, I've been researching new classes of side-channel vulnerabilities (check out [Pixnapping](https://www.pixnapping.com)), building practical defenses for the novel side-channel vulnerabilities, and studying new techniques for microarchitectural reverse engineering. 
I'm currently advised by [Professor Chris Fletcher](https://cwfletcher.github.io/) at the University of California, Berkeley. 

I work with several undergraduate students across several universities. 
Please see my [CV](/assets/cv.pdf) for the full list. 

If you are an undergrad and want to work with me, please see [this](/working-with-me).

# Publications
<ul>
{% for pub in site.data.publications %}{% include publication.html pub=pub %}
{% endfor %}
</ul>

# Theses
<ul>
{% for thesis in site.data.theses %}{% include publication.html pub=thesis %}
{% endfor %}
</ul>