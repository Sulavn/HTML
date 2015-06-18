# HTML

<!doctype html>

<html>
 <head>
   <title> Pirate Translator</title>
 </head>

 <body>
   <p align="center"><img id="Image1" onmouseover="this.src = 'http://upload.wikimedia.org/wikipedia/commons/thumb/4/47/Pirate_Flag_of_Jack_Rackham.svg/2000px-      Pirate_Flag_of_Jack_Rackham.svg.png'" onmouseout="this.src = 'http://upload.wikimedia.org/wikipedia/commons/thumb/7/71/Piratey,_vector_version.svg/789px-Piratey,_vector_version.svg.png'"       "border=0" src="http://upload.wikimedia.org/wikipedia/commons/thumb/7/71/Piratey,_vector_version.svg/789px-Piratey,_vector_version.svg.png" alt="Pirate" height="360" width="360"></center>

		
   <h3>Land Lubber's Pirate Translator</h3>
   <p>Simply click on the buttons to translate
      words and/or phrases from English to pirate talk.
   </p>
   <p>
   <table>
	<th>Greetings</th>
	<th>People</th>
	<th>Questions</th>
	<th>Articles</th>
	<th>Places</th>
  	<tr>
     		<td><input type="button" value="hello" 
            		onclick="document.getElementById('outputDiv').innerHTML= 
                       		document.getElementById('outputDiv').innerHTML + 'ahoy ';"></td>
     		<td><input type="button" value="stranger" 
            		onclick="document.getElementById('outputDiv').innerHTML = 
                       		document.getElementById('outputDiv').innerHTML + 'scurvy dog ';"></td>
		<td><input type="button" value="where is" 
            		onclick="document.getElementById('outputDiv').innerHTML = 
                      		 document.getElementById('outputDiv').innerHTML + 'whar be ';"></td>
		<td><input type="button" value="The" 
           		 onclick="document.getElementById('outputDiv').innerHTML= 
                       		document.getElementById('outputDiv').innerHTML + 'th\' ';"></td>
		<td><input type="button" value="Restroom" 
            		onclick="document.getElementById('outputDiv').innerHTML = 
                      		 document.getElementById('outputDiv').innerHTML + 'head ';"></td>
  	</tr>
	<tr>
		<td><input type="button" value="pardon me" 
            		onclick="document.getElementById('outputDiv').innerHTML= 
                       		document.getElementById('outputDiv').innerHTML + 'avast ';"></td>
       		<td><input type="button" value="Sir" 
            		onclick="document.getElementById('outputDiv').innerHTML= 
                       		document.getElementById('outputDiv').innerHTML + 'matey ';"></td>
		<td><input type="button" value="can you help me find" 
           		 onclick="document.getElementById('outputDiv').innerHTML= 
                  		     document.getElementById('outputDiv').innerHTML + 'know ye ';"></td>
		<td><input type="button" value="My" 
            		onclick="document.getElementById('outputDiv').innerHTML = 
                       		document.getElementById('outputDiv').innerHTML + 'me ';"></td>
		<td><input type="button" value="Restaurant" 
            		onclick="document.getElementById('outputDiv').innerHTML= 
                     		  document.getElementById('outputDiv').innerHTML + 'galley ';"></td>
	</tr>
	<tr>	
		<td><input type="button" value="excuse me" 
            		onclick="document.getElementById('outputDiv').innerHTML = 
                       		document.getElementById('outputDiv').innerHTML + 'arrr ';"></td>
		<td><input type="button" value="Madam" 
			onclick="document.getElementById('outputDiv').innerHTML = 
                    		document.getElementById('outputDiv').innerHTML + 'proud beauty ';"></td>
		<td><input type="button" value="is that" 
           		onclick="document.getElementById('outputDiv').innerHTML = 
                   		document.getElementById('outputDiv').innerHTML + 'be that ';"></td>
		<td><input type="button" value="Your" 
            		onclick="document.getElementById('outputDiv').innerHTML= 
                       		document.getElementById('outputDiv').innerHTML + 'yer ';"></td>
		<td><input type="button" value="Hotel" 
            		onclick="document.getElementById('outputDiv').innerHTML = 
                       		document.getElementById('outputDiv').innerHTML + 'fleabag inn ';"></td>
  	</tr>
	<tr>
		<td></td>
		<td><input type="button" value="Officer" 
         		   onclick="document.getElementById('outputDiv').innerHTML= 
                    		   document.getElementById('outputDiv').innerHTML + 'foul blaggart ';"></td>
		 
   </table>
    
     
     
     
     <br>
     <input type="button" value="clear" 
            onclick="document.getElementById('outputDiv').innerHTML ='';">
     <input type="button" value="return" 
            onclick="document.getElementById('outputDiv').innerHTML = 
                       document.getElementById('outputDiv').innerHTML + '<br>';">
   </p>
   <hr>
   <div id="outputDiv"></div>
   <p align="center"><img id="Image2" "border=0" 
	src="http://upload.wikimedia.org/wikipedia/commons/thumb/4/47/Pirate_Flag_of_Jack_Rackham.svg/2000px-Pirate_Flag_of_Jack_Rackham.svg.png" alt="Flag" height="360" width="360"></center>

 </body>
</html>
 
