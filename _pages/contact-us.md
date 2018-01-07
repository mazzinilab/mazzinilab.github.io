---
title: "Contact us"
layout: textlay
excerpt: "COLAB -- Contact us."
sitemap: false
permalink: /contact-us/
---

<br>

<div class="container-fluid">
<div class="row">

<div class="col-sm-4">
<div style="text-align:justify" markdown="1">
<p> Dr. Piero Mazzini <br>
Estuary & Ocean Science Center <br>
San Francisco State Romberg Tiburon Campus <br>
3150 Paradise Dr, Bldg 36 <br>
Tiburon, CA 94920 </p>
<span class="glyphicon glyphicon-phone-alt"></span> +1 (415) 338-3706 <br>
<i class="glyphicon glyphicon-envelope"></i> <pmazzini@sfsu.edu>
</div>
</div>

<div class="col-sm-8">
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/contapic/rtc_front.jpg" class="img-responsive" width="500px" height="auto" alt="EOS" />
<figcaption> EOS Center - Main Building
</figcaption>
</figure>
</div>

</div>
</div>


<div class="container-fluid">
<div class="row">

<div class="col-sm-6">
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/contapic/rtc_above.jpg" class="img-responsive" width="490px" height="auto" alt="RTC"/>
<figcaption> Romberg Tiburon Campus
</figcaption>
</figure>
</div>

<div class="col-sm-6">
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/contapic/questuary.png" class="img-responsive" width="490px" height="auto" alt="questuary" />
<figcaption> R/V Questuary
</figcaption>
</figure>
</div>

</div>
</div>




#### Directions to the Estuary & Ocean Science Center (EOS Center) (Romberg Tiburon Campus):

<div id="map" style="width:100%;height:500px"></div>

<script>
function myMap() {
  var myCenter = new google.maps.LatLng(37.8890,-122.4492);
  var mapCanvas = document.getElementById("map");
  var mapOptions = {center: myCenter, zoom: 11};
  var map = new google.maps.Map(mapCanvas, mapOptions);
  var marker = new google.maps.Marker({position:myCenter});
  marker.setMap(map);

  var infowindow = new google.maps.InfoWindow({
  content: "3150 Paradise Drive, Bldg 36 - Tiburon, California"
});
infowindow.open(map,marker);
}
</script>

<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyA7i6vSafRzNMdIaq-SslU9oycP9HMR9TM&callback=myMap">
</script>

<br>
