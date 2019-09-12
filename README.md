# JavaScript-1

### What is javascript:
	It is a Clicnt side script Language or Browser Language. 
	Client side script Language means it execute/run the browser.
	javascript it's a "case sensetive".

### Javascript make a 3 parts:
	1) ECMAscript : "European Computer Manufacturer's Association" Its main parts of  javascript. 
		its alternative name Core funtionality.
	2) DOM: "Document Object Model". Its work web page content.
	3) BOM: "Browser Object Model". Its work Browser.

### Javascript Effects:
	Javascript help HTML page created many effects. Its working form validation.

### Effects:
	1) Watch Create 
	2) Mouse Trailers 
	3) Dropdown Menu 
	4) Alert Message 
	5) Popup window 
	6) slide show 
	7) Running news 
	8) Form Validation etc.

### kinds of Javascript:
	1) Internal: use to head or body dection with script tag. 
		     Always js use head seection because its working better.
		Example: <head>
			  <script>
				you write a javascript coding.
		                      </script>
		                 </head>
	2) External: you create a (.js) external file and you link this html page. 
		     you link external file by script tag.
		     Always write body end section but its head body two section working.
		   Example: <script src="main.js" type="text/javascript"></script> 

### javascript comments:
		Single line comments you use 2 slash ~ (//content )
		Multiple Line comments you use  ~ ( */ content */ )

### Javascript/Programing all method: 5 parts of js

	1) Data Type:  2 Parts of Data type. (1) Scaler Type  (2) Composite type
	
	            Scaler type: 5 parts of  Scaler type
	     =========================
		i) Number : 2 parts
		      1) Integer: Its a Integer value.. 1,2,3,4,55,111,-22,-258,-500 (nrgative & positive integer value)
		      2) Floating: Its a decimal value... 2.2, 5.22, 6.365, 5.21587
		-------------------------------------------------------------------------------
		ii) Boolean : Its a two value.
		      1) True ( true equal 1 )
		      2) False ( false equal 0 )
		--------------------------------------------------------------------
		iii) String : Any text/content js call to string. 
			string always stay single ('content') or double quatation ("content")
		-----------------------------------------------------
		iv) Undefined : you declare variable but dont assign Data type value , 
				its data type declare undefined.
		--------------------------------------------------------------------
		v) Null : Undefinded & null almost same. one diiferent of undefined. 
			  null always assign null but undefiend dont assign undefined.
		          null is a blank object. 

	              (EX):
			  <script>
				   var multi;              (Undefiend)
				   document.write (typeof multi+ '<br/>') ;

				   var multi = 'Hi multi';    ( string)
				   document.write (typeof multi  + '<br/>');

				   var multi = 15;      (Number)
				   document.write (typeof multi + '<br/>');

				   var multi = 20.325; (number)
				   document.write (typeof multi + '<br/>');

				  var multi = false;    ( boolean)
				  document.write (typeof multi + '<br/>');

				 var multi = null;      (object)
				 document.write (typeof multi + '<br/>');
			</script>


	        Composite Type: 2 parts of Composite Type.
	   ================================
		i) Array: Its start Third Brackets --  [ ]
			Define: (var var_name= elements)
			EX: var fruits= ['apple','banana','orange','malta'];
			        document.write(fruits[2] + '<br />');
		ii) Object: Ita start Second Brackets -- { } 
		            Define: (var var_name= elements)
		            EX: var color= {  	
			"0": 'teal',
			"1": 'red',
			"2": 'grey',
			"3": 'yellow',
			"4": 'orange',
				}
			document.write(color[1] + '<br />');
		
	2) Control flow : 2 types of control flow.
		i) Iterative: This is loop ( for, while )
			Define: (variable initialization; Condition; Last Expression)
			(EX):  ( for )
			         for( s = 10; s > 0; s--){
			          document.write(s + '<br />');
			          }

			( OR )
			          var s;
			          for( s = 10; s > 0; s--){
			          document.write(s + '<br />');
				}

			(EX):  ( While )
			          var i = 0;
			          while( i < 50){
		   	                if(i % 2 != 0){
			                    document.write(i + '<br/>');
		      	                   }
		  	             i++;
	   		            }

		ii) Conditional ( if, else, else if )

			(EX): ( if )
			        var color = 'blue';
			        if(color == 'blue'){
			        document.write('just like the sky !');
		     	        } 

			(EX): ( if_else )
			       var color = 'blue';
			        if(color=='red'){
			        document.write('This is my fantasy WORLD!');
			              }
			        else{
			        document.write('This is not my Fantasy WORLD!');
			             }

			(EX): ( if_else if_else )
			       var color="blue";
			       if (color=="red"){ 
			       document.write('HELLO WORLD');
			            }
			        else if (color=="green"){
			        document.write("Fantasy WORLD!");
			               }
			        else if ( color=="blue"){
			        document.write('SRK WORLD!');
			             }
			        else{
			        document.write("my world!");
			             }
	3) Variable : Its call a container. many value reserve the container/jar. Variable it's a "Case Sensetive".
		(EX): Var Var_name = Value;
		         var x = 'sarwar'; 

		        ( OR )
		         x = 'sarwar'; (you write 'var' or dont write 'var' same working);

		(EX):
			var my_var = 'This is my amazing world';
			document.write(my_var);
			document.write('<br />');
			var read = 'This is my first paragraph';
			document.write(read + '<br />');
			var color = 'This is my favourite color';
			document.write(color + '<br />');
			var number1 = 222;
			var number2 = 222;
			document.write(number1+number2);
	4) Fuction : Function is a codeblock , you call this codeblock and its execute this thing.
		 Function make two ways.
		       i) Build in function. (This Function JS Build In Function)
			1) JavaScript Array Function --> ["Apple","Orange"];
			2) JavaScript Boolean Function -->True, false
			3) JavaScript Math Function --> 22+55	 
			4) JavaScript Date Function --> 22.10.2019
			5) JavaScript Number Function --> 25
			6) JavaScript String Function -- "Apple"
			7) JavaScript RegExp Function (RegExp-Regukar Expression)

		       ii) User define function. (You can create any function of User define function. 
		       		Always you function name write 'lower Case', or its show Error)
		            Define : Function Function_Name(var1,var2)
				{
				statements
		                  		  }
	
		               (EX):
			function multi(a,b){
			       return a*b;
			         }
			document.write(multi(4,3));

	5) Operator : Its more mathmatical symbol. its call operator. 
			(Ex):   + - * / = < >


### You Close every statement this ( ; ) symbol

***
## G SARWAR
#### Web Instructor
