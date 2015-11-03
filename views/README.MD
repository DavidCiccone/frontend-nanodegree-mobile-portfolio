Change made to the main.js file in views/js/main.js

Line 452, in the function chagePizzaSize:
	-Created Variable pizzaSizee to hold document.querySelectorAll
		
	-Changed querySelectorAll to getElementsByClassName as this is faster.
	
	-Moved the variable within the loop out of it and shortend them using the pizzaSizee variable.
		

Line 479: 
	Moved document.getElementById("randomPizzas") out of the for loop into it's own variable.	


Line 513 and 515:
	Created variable newVar and items.  These are pieced removed from the for loop which can be call once before the loop run rather than being each time.


Line 534 and 537:
	Added requestAnimation Frame.


Line 546:
	Removed the height and width from the loop and moved them to the css file.  This reduced scripting time since they are not called each time the page scrolls.
