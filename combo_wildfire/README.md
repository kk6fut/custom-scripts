# Enhanced wildfire visualization using S2LSA and S3SLSTR

---

## Author
Benjamin F. Kuo

## Purpose

s script uses a combination of two different satellites -- S2L2A and S3SLTR -- to better highlight areas burning due to wildfires. The way this script works is it adjusts the brightness of the S2L2A, true color image using a scaled value of the S3SLSTR F2 value, which increases the brightness of areas that are burning, and decreases the value of areas which are not burning.

---

<a href="#" id='togglescript'>Show</a> script or [download](script.js){:target="_blank"} it.
<div id='script_view' style="display:none">
{% highlight javascript %}
      {% include_relative script.js %}
{% endhighlight %}
</div>

## Evaluate and visualize
 - [Sentinel Playground](https://apps.sentinel-hub.com/sentinel-playground/?source=S2&lat=41.9027835&lng=12.496365500000024&zoom=12&evalscripturl=https://raw.githubusercontent.com/kk6fut/custom-scripts/master/combo_wildfire/script.js){:target="_blank"}    
 - [EO Browser](http://apps.sentinel-hub.com/eo-browser/#lat=41.9&lng=12.5&zoom=10&datasource=Sentinel-2%20L1C&time=2017-10-08&preset=CUSTOM&layers=B01,B02,B03&evalscripturl=https://raw.githubusercontent.com/kk6fut/custom-scripts/master/combo_wildfire/script.js){:target="_blank"}   

## General description of the script

## References
 - possible references (scientific articles, wiki/web references, ...)
