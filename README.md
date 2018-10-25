/*******************************
GENERAL
********************************/
/*FONT OF THE CONTENT OF THE */
body{
	font-family: 'Open Sans' , sans-serif;
}

/*FIXING THE DIV*/
#wrapper {
	max-width: 940px;
	margin: 0 auto;
	padding:0 10%;
	
}

/*REMOVE ASTERISK TO THE LINK*/
a{
	text-decoration: none;		
}

img{
	max-width: 100%;
}

/*******************************
HEADING
********************************/
header{
	float: right;
	margin: 0 0 30px 0;
	padding: 5px 0 0 0;
	width: 100%;
}

#logo{
	text-align: center;
	margin: 0;
	color:#fff;
	
	
	@media only screen and (max-width: 479px){ /*for smartphone*/

	#gallery li:nth-child(4n){
		clear: none;
	}
	#gallery li:nth-child(3n){
		clear: left;
	}
	
}

@media only screen and (min-width: 480px){ /*for smartphone*/

	#primary{
		float: left;
		width: 50%;
				
	}
	#secondary{
		float: right;
		width: 40%;
	}
	#gallery li{
		width: 28.3333%;
	}
	#gallery li:nth-child(4n){
		clear: left;
	}
	.profile-picture{
		float: left;
		margin: 0 50px 0 0;
	}
}
@media screen and (min-width: 660px){ /*for tablet*/
	
	nav{
		float: right;
		background: none;
		text-align: right;
		margin-right: 5%;
		width: 45%;
		font-size: 1.125em;
	}
	nav li{
		margin-right: 0;
	}
	#logo{
		float: left;
		text-align: left;
		margin-left: 5%;
		width: 45%;
}
h1{
	font-family: 'Changa One', sans-serif;
	margin: 15px 0;
	font-size: 1.75em;
	font-weight:normal;
	line-height: 0.8em;
}
h2{
	font-size: 0.75em;
	margin: -5px 0 0;
	font-weight: normal;
}

/*******************************
NAVIGATION
********************************/

nav{
	text-align: center;
	padding: 10px 0;
	margin: 20px 0 0;
}
nav ul{
	list-style: none;
	padding: 0;
	margin:0 10px;
}
nav li{
