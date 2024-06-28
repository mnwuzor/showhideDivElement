## showhideDivElement
This script is to help anyone that wants to integrate a Hide/Show DIV element in their web application. 

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

 And also a little tweek on the CSS
 
 	<style> 
		.hideDiv { 
			display: none; 
			justify-content: center; 
		} 

		.button-container { 
			display: inline; 
			justify-content: center; 
			margin-top: 20px; 
		} 
		.clickbutton {
		  background-color: red;
		  border: none;
		  color: white;
		  padding: 5px 5px;
		  text-align: center;
		  text-decoration: none;
		  display: inline-block;
		  font-size: 14px;
		  margin: 4px 2px;
		  cursor: pointer;
		}	
		.buttonRed{
			background-color: #f44336;
			}	
		.buttonRed:hover{
			background-color: #f44336;
			color: white;
			} 
	</style> 

The easiest way to understand how to use it is to first use it the way it and then make changes line by line. A knowldge of JavaScript and CSS will be needed here though.
