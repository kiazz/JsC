<!DOCTYPE html>
<html>
<head>
	<title>JSC Test Suite</title>
	<link rel="stylesheet" href="http://code.jquery.com/qunit/qunit-1.14.0.css">
	<link rel="stylesheet" href="jquery.seat-charts.css">
	<script src="http://code.jquery.com/qunit/qunit-1.14.0.js"></script>
	<script src="http://code.jquery.com/jquery-1.11.1.min.js"></script>
	<script type="text/javascript" src="jquery.seat-charts.min.js"></script>

	<script type="text/javascript" src="general.js"></script>
	<script type="text/javascript" src="methods.js"></script>
	<script type="text/javascript" src="interactions.js"></script>
	<script type="text/javascript" src="multiple.js"></script>
</head>
<body>
	$(document).ready(function() {

	var sc = $('#seat-map').seatCharts({
		map: [
			'aaaaaaaaaaaa',
			'aaaaaaaaaaaa',
			'bbbbbbbbbb__',
			'bbbbbbbbbb__',
			'bbbbbbbbbbbb',
			'cccccccccccc'
		],
		seats: {
			a: {
				price   : 99.99,
				classes : 'front-seat' //your custom CSS class
			}
		
		},
		click: function () {
			if (this.status() == 'available') {
				//do some stuff, i.e. add to the cart
				return 'selected';
			} else if (this.status() == 'selected') {
				//seat has been vacated
				return 'available';
			} else if (this.status() == 'unavailable') {
				//seat has been already booked
				return 'unavailable';
			} else {
				return this.style();
			}
		}
	});

	//Make all available 'c' seats unavailable
	sc.find('c.available').status('unavailable');
	
	/*
	Get seats with ids 2_6, 1_7 (more on ids later on),
	put them in a jQuery set and change some css
	*/
	sc.get(['2_6', '1_7']).node().css({
		color: '#ffcfcf'
	});
	
	console.log('Seat 1_2 costs ' + sc.get('1_2').data().price + ' and is currently ' + sc.status('1_2'));

});
</body>
</html>
