<div id="mapCanvas" style="top: 10px;left: 75px; width:210px; height:220px"></div>
<div id="map2"></div>
<!-- Replace the value of the key parameter with your own API key. -->
<script async defer src="https://maps.googleapis.com/maps/api/js?key=AIzaSyARQmuqwYrdxIhqDoZSIepLGULvhnvmEYk&callback=initMap">


</script>

# maps
var LtLg = new google.maps.LatLng(43.761538,-79.411079 );
var LtLg2 = new google.maps.LatLng(43.518299,-79.684999 );
var Tor = {
	center: LtLg,
  zoom: 10
};
var Abf = {
	center: LtLg2,
  zoom: 10
};
	
  var map = new google.maps.Map(document.getElementById('mapCanvas'), mapTor);
  var image = {
    url: 'http://www.truckdriver.com/truckdriverimages/ProfileImages/201.jpg',
    scaledSize: new google.maps.Size(100, 28),
    origin: new google.maps.Point(0, 0),
    anchor: new google.maps.Point(50, 10)
  };
  

}
