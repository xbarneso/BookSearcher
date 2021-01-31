# BookSearcher
Very simple app. 
By console you have to type one book Name. 
Then, a Frame will be displayed with the Book image, the title, the author, the publisher, release date and the description. 


It works with Google api. So, there are many classes structured as: 

MainProgram class to start the program. 
Controller to flow throw the process. 
Menu to display the text in the console. 
APIhandler to get the information from Google Api. 
Abstract factory > Book Factory to create the book object. 
Book object > with all the book info to be displayed. 
Frame class to display the book. 
