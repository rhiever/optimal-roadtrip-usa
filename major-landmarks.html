<!DOCTYPE html>
<html lang="en">
  <head>
  	<meta charset="utf-8">
    <meta name="viewport" content="initial-scale=1.0, user-scalable=no">
    <meta name="description" content="Randy Olson uses machine learning to find the optimal road trip across the U.S.">
    <meta name="author" content="Randal S. Olson">
    
    <title>The optimal road trip across the U.S. according to machine learning</title>
    <style>
      html, body, #map-canvas {
        height: 100%;
        margin: 0px;
        padding: 0px
      }
      #panel {
        position: absolute;
        top: 5px;
        left: 50%;
        margin-left: -180px;
        z-index: 5;
        background-color: #fff;
        padding: 10px;
        border: 1px solid #999;
      }
    </style>
    <script src="https://maps.googleapis.com/maps/api/js?v=3.exp&signed_in=true"></script>
    <script>
		var directionsDisplay1, directionsDisplay2;
		var directionsDisplay3, directionsDisplay4;
		var directionsDisplay5, directionsDisplay6;
		var markerOptions = {icon: "http://maps.gstatic.com/mapfiles/markers2/marker.png"};
		var directionsDisplayOptions = {preserveViewport: true,
										markerOptions: markerOptions};
		var directionsService = new google.maps.DirectionsService();
		var map;

		function initialize() {
		  var center = new google.maps.LatLng(39, -96);
		  var mapOptions = {
			zoom: 5,
			center: center
		  };
		  map = new google.maps.Map(document.getElementById('map-canvas'), mapOptions);
		  directionsDisplay1.setMap(map);
		  directionsDisplay2.setMap(map);
		  directionsDisplay3.setMap(map);
		  directionsDisplay4.setMap(map);
		  directionsDisplay5.setMap(map);
		  directionsDisplay6.setMap(map);
		}

		function calcRoute(start, end, routes) {
		  switch (start) {
		  	case "Grand Canyon National Park Lodges, 88 Village Loop Drive, Grand Canyon Village, AZ 86023":
		  		directionsDisplay1 = new google.maps.DirectionsRenderer(directionsDisplayOptions);
		  		break;
		  	case "Graceland, Elvis Presley Boulevard, Memphis, TN":
		  		directionsDisplay2 = new google.maps.DirectionsRenderer(directionsDisplayOptions);
		  		break;
		  	case "Mount Vernon, Fairfax County, Virginia":
		  		directionsDisplay3 = new google.maps.DirectionsRenderer(directionsDisplayOptions);
		  		break;
		  	case "USS Constitution, Boston, MA":
		  		directionsDisplay4 = new google.maps.DirectionsRenderer(directionsDisplayOptions);
		  		break;
		  	case "Lincoln Home National Historic Site Visitor Center, 426 South 7th Street, Springfield, IL":
		  		directionsDisplay5 = new google.maps.DirectionsRenderer(directionsDisplayOptions);
		  		break;
		  	case "Glacier National Park, 64 Grinnell Drive, West Glacier, MT 59936":
		  		directionsDisplay6 = new google.maps.DirectionsRenderer(directionsDisplayOptions);
		  		break;
		  }
		  
		  var waypts = [];
		  for (var i = 0; i < routes.length; i++) {
		  	waypts.push({
		  	  location:routes[i],
		  	  stopover:true});
		  	}
		  
		  var request = {
			  origin: start,
			  destination: end,
			  waypoints: waypts,
			  optimizeWaypoints: false,
			  travelMode: google.maps.TravelMode.DRIVING
		  };
		  directionsService.route(request, function(response, status) {
			if (status == google.maps.DirectionsStatus.OK) {
				switch (start) {
					case "Grand Canyon National Park Lodges, 88 Village Loop Drive, Grand Canyon Village, AZ 86023":
						directionsDisplay1.setDirections(response);
						break;
					case "Graceland, Elvis Presley Boulevard, Memphis, TN":
						directionsDisplay2.setDirections(response);
						break;
					case "Mount Vernon, Fairfax County, Virginia":
						directionsDisplay3.setDirections(response);
						break;
					case "USS Constitution, Boston, MA":
						directionsDisplay4.setDirections(response);
						break;
					case "Lincoln Home National Historic Site Visitor Center, 426 South 7th Street, Springfield, IL":
						directionsDisplay5.setDirections(response);
						break;
					case "Glacier National Park, 64 Grinnell Drive, West Glacier, MT 59936":
						directionsDisplay6.setDirections(response);
						break;
				  }
			}
		  });
		}

		google.maps.event.addDomListener(window, 'load', initialize);
		
		calcRoute("Grand Canyon National Park Lodges, 88 Village Loop Drive, Grand Canyon Village, AZ 86023",
					"Graceland, Elvis Presley Boulevard, Memphis, TN",
					["Bryce Canyon National Park, Hwy 63, Bryce, UT",
					"Craters of the Moon National Monument & Preserve, Arco, ID",
					"Yellowstone National Park, WY 82190",
					"Pikes Peak, Colorado",
					"Carlsbad Caverns National Park, Carlsbad, NM",
					"The Alamo, Alamo Plaza, San Antonio, TX",
					"Chickasaw National Recreation Area, 1008 W 2nd St, Sulphur, OK 73086",
					"Toltec Mounds, Scott, AR"]);
					
		calcRoute("Graceland, Elvis Presley Boulevard, Memphis, TN",
					"Mount Vernon, Fairfax County, Virginia",
					["Vicksburg National Military Park, Clay Street, Vicksburg, MS",
					"French Quarter, New Orleans, LA",
					"USS Alabama, Battleship Parkway, Mobile, AL",
					"Cape Canaveral, FL",
					"Okefenokee Swamp Park, Okefenokee Swamp Park Road, Waycross, GA",
					"Fort Sumter National Monument, Sullivan's Island, SC",
					"Lost World Caverns, Lewisburg, WV",
					"Wright Brothers National Memorial Visitor Center, Manteo, NC"]);
					
		calcRoute("Mount Vernon, Fairfax County, Virginia",
					"USS Constitution, Boston, MA",
					["White House, Pennsylvania Avenue Northwest, Washington, DC",
					"Maryland State House, 100 State Cir, Annapolis, MD 21401",
					"New Castle Historic District, Delaware",
					"Congress Hall, Congress Place, Cape May, NJ 08204",
					"Liberty Bell, 6th Street, Philadelphia, PA",
					"Statue of Liberty, Liberty Island, NYC, NY",
					"The Mark Twain House & Museum, Farmington Avenue, Hartford, CT",
					"The Breakers, Ochre Point Avenue, Newport, RI"]);
					
		calcRoute("USS Constitution, Boston, MA",
					"Lincoln Home National Historic Site Visitor Center, 426 South 7th Street, Springfield, IL",
					["Acadia National Park, Maine",
					"Omni Mount Washington Resort, Mount Washington Hotel Road, Bretton Woods, NH",
					"Shelburne Farms, Harbor Road, Shelburne, VT",
					"USS Cod Submarine Memorial, East 9th Street, Cleveland, OH",
					"Olympia Entertainment, Woodward Avenue, Detroit, MI",
					"Spring Grove Cemetery, Spring Grove Avenue, Cincinnati, OH",
					"Mammoth Cave National Park, Mammoth Cave Pkwy, Mammoth Cave, KY",
					"West Baden Springs Hotel, West Baden Avenue, West Baden Springs, IN",
					]);
					
		calcRoute("Lincoln Home National Historic Site Visitor Center, 426 South 7th Street, Springfield, IL",
					"Glacier National Park, 64 Grinnell Drive, West Glacier, MT 59936",
					["Gateway Arch, Washington Avenue, St Louis, MO",
					"C. W. Parker Carousel Museum, South Esplanade Street, Leavenworth, KS",
					"Terrace Hill, Grand Avenue, Des Moines, IA",
					"Taliesin, County Road C, Spring Green, Wisconsin",
					"Fort Snelling, Tower Avenue, Saint Paul, MN",
					"Ashfall Fossil Bed, Royal, NE",
					"Mount Rushmore National Memorial, South Dakota 244, Keystone, SD",
					"Fort Union Trading Post National Historic Site, Williston, North Dakota 1804, ND",
					]);
						
		calcRoute("Glacier National Park, 64 Grinnell Drive, West Glacier, MT 59936",
					"Grand Canyon National Park Lodges, 88 Village Loop Drive, Grand Canyon Village, AZ 86023",
					["Hanford Site, Benton County, WA",
					"Columbia River Gorge National Scenic Area, Oregon",
					"Cable Car Museum, 94108, 1201 Mason St, San Francisco, CA 94108",
					"San Andreas Fault, San Benito County, CA",
					"Hoover Dam, Boulder City, CO"]);
    </script>
  </head>
  <body>
    <div id="map-canvas"></div>
  </body>
</html>
