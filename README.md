# INstructions

Download the 7z compressed file and extract it to your directory

Change the path location of the SQLite database in the .env file

#Getting the Categories URI
http://127.0.0.1:8000/api/categories

#Getting a Specific Category
http://127.0.0.1:8000/api/categories/<id>
  
#Post to Category
http://127.0.0.1:8000/api/categories
#JSON to post to Category
{
	"name" : "Shirts", 
	"parentCategory": 1, 
	"isVisible": 1
}
  
#Patch Category
http://127.0.0.1:8000/api/categories/11
#JSON to change visibility for Patch Category (1: Visible; 0: Hide)
{
	"isVisible": 0
}
