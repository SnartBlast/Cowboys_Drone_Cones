
NOTES ON DJANGO TEMPLATES

	Django templates work essentially as html files. However, usual html embedded elements such as:
		. links to other html files
		. images 
		. css file

		are managed by other elements of the Django project. 

	
	Django templates should follow general template:

	---------------------------------------------------------
	<!DOCTYPE html>
	<html lang="en">
		<head>
			<meta charset="utf-8"/>
			<title>title_text</title>
		</head>
		<body>

			--> Contents of the page goes here <--


		</body>
	</html>
	---------------------------------------------------------


HTML REVIEW

	    <a/>  -->  link tag
	 <body/>  -->  body tag
	  <nav/>  -->  navigation bar tag
	 <link/>  -->  connector to a css file, ex: 
			<link rel="stylesheet type="text/css" href="{file name}"/>

	<aside/>  -->  make a side tab



CSS REVIEW

	css file structure: 

	{element:specifier} {
		color: {choice};
		background-color: {choice};
		text-align: {choice};
		font-family: {choice};
		font-size: {choice};	

	}


 style="background-color:c0c0c0;border-style:inset;border-width:thick">
