js-ready
========

JavaScript only version of jQuery's document.ready method

Example
-------

	<script type="text/javascript" src="../dist/js-ready.js"></script>
	<script type="text/javascript">
	ready(function(){
		document.getElementById('updated-on-ready').innerHTML = 'This was added after the DOM was loaded.';
	});
	</script>


