
<!DOCTYPE html>
<html>
<head>
<meta charset=utf-8 />
<title>State of the City</title>
<meta name='viewport' content='initial-scale=1,maximum-scale=1,user-scalable=no' />
<meta name="description" content="Hackster Amazon IoT Contest entry : State of the City creates a map of your city using crowdsourced data " />
<meta name="author" content="Anuj Deshpande"/>
<script src='https://api.mapbox.com/mapbox.js/v2.2.3/mapbox.js'></script>
<!-- <script src='https://sdk.amazonaws.com/js/aws-sdk-2.2.28.min.js'></script> -->
<script src='http://code.jquery.com/jquery-latest.js'></script>
<link href='https://api.mapbox.com/mapbox.js/v2.2.3/mapbox.css' rel='stylesheet' />

<style>
  body { margin:0; padding:0; }
  #map { position:absolute; top:0; bottom:0; width:100%; }
</style>
</head>

<body>

<div id='map'></div>

<script>
var thing1 = 'na';
var thing2 = 'na';
getstuff();



function getstuff(){

  $.get( "https://s3-us-west-2.amazonaws.com/stateofthecity/thing1.json", function( data ) {
    var items = [];
    data = data.replace('\0','');
    // data = JSON.parse(data);
    var d = JSON.parse(data);
    // console.log(d.state.reported.temperature);
    window.thing1 = String(d.state.reported.temperature);
  });



$.get( "https://s3-us-west-2.amazonaws.com/stateofthecity/thing2.json", function( data ) {
  var items = [];
  data = data.replace('\0','');
  // data = JSON.parse(data);
  var d = JSON.parse(data);
     window.thing2 = String(d.state.reported.temperature);

});

setTimeout(function(){ domapbox(); }, 5000);

};

function domapbox(){

L.mapbox.accessToken = 'pk.eyJ1IjoiYW51amRlc2hwYW5kZSIsImEiOiJjaWZ6NXpoM2E1cDFjdXdrcnF0eHU0MHA2In0._Sm9QJXwbZPEreM7tlQlAQ';
var map = L.mapbox.map('map', 'mapbox.streets')
    .setView([18.5, 73.9], 9);

L.mapbox.featureLayer({
    // this feature is in the GeoJSON format: see geojson.org
    // for the full specification
    type: 'Feature',
    geometry: {
        type: 'Point',
        // coordinates here are in longitude, latitude order because
        // x, y is the standard for GeoJSON and many formats
        coordinates: [
          73.894818,
          18.5504573
        ]
    },
    properties: {
        title: 'Thing1',
        description: window.thing1,
        'marker-size': 'large',
        'marker-color': '#BE0000',
        'marker-symbol': 'commercial'
}
}).addTo(map);

L.mapbox.featureLayer({
    // this feature is in the GeoJSON format: see geojson.org
    // for the full specification
    type: 'Feature',
    geometry: {
        type: 'Point',
        // coordinates here are in longitude, latitude order because
        // x, y is the standard for GeoJSON and many formats
        coordinates: [
          73.828327,
          18.526307
        ]
    },
    properties: {
        title: 'Thing2',
        description: window.thing2,
        'marker-size': 'large',
        'marker-color': '#BE006B',
        'marker-symbol': 'industrial'
}
}).addTo(map);
};
</script>
</body>
</html>
