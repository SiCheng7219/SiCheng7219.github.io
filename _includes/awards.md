<h2 id="publications" style="margin: 2px 0px -15px;">Awards</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}

<li>
<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% if link.image %} 
      <img src="\assets\img\meisai.png" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
    {% endif %}
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.pdf }}">Finalist in 2022 Mathematical Contest in Modeling</a></div>
      <div class="author">Sicheng Jiang, Zimo Wang, Meitong Li</div>
      <div class="periodical">
        <a herf="https://www.comap.com/contests/mcm-icm">The Mathematical Contest in Modeling (MCM)® 2022</a>
      </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="https://www.comap-math.com/mcm/2022Certs/2203036.pdf" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.source %} 
      <a href="[{{ link.code }}](https://www.comap-math.com/mcm/2022Certs/2203036.pd)" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Source</a>
      {% endif %}
    </div>
  </div>
</div>
</li>




<br>

{% endfor %}

</ol>
</div>

