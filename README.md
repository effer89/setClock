# setClock

For those who need a JS clock with the ability to set your own time.

<script src="js/plugin.js"></script>
	<script>
		$(document).ready(function() {
			var clock = $('#set-clock');
			
			// init
			clock.setClock();
			
			// after a while, set system time, you can also, pass just the timestamp without Date()
			setTimeout(function(){
				clock.setClock.setTime(new Date(1395965183631));
			},5000);
		});
	</script>
