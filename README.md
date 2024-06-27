## showhideDivElement
This script is to help those that want to integrate a DIV How/Show element in their web application. 

It's quite easy to use. Simply edit the code below to suit your need

	<script> 
		$('#click').on('click', function () { 
			if ($('#click').text() === 'No! Hide Box') { 

				// This block is executed when 
				// you click the show button 
				$('#click').text('Show'); 
				$('#element').css('display', 'none'); 
			} 
			else { 

				// This block is executed when 
				// you click the hide button 
				$('#click').text('No! Hide Box'); 
				$('#element').css('display', 'inline'); 
			} 
		}); 
	</script> 

 
