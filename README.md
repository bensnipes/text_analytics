# text_analytics
This is an application that analyses texts to determine its suitability for readers(young, old, middle-aged)

Code
The first couple of jupyter cells imports all the needed libraries the application requires
to run. You'd have to install the libraries if you do not have it already using pip.

The main jupyter cell is made up of a couple of tkinter codes. Tkinter is a known graphic
interface library for python. 

Once you run the cell, an interface should pop up.

The interface should be mainly divided into two parts; left and right. Each side should have
five buttons namely; "upload script", "analyze", "visualize", "recommend" and "exit".

The upload script button is used to the text to be analyzed. The text formats supported are
pdf, docx and txt. Once uploaded, you should select the analyze button. The analyze button 
analyses the text and prints out information about the text.

The visualize button visualizes the analyzed output in the form of a pie chart and word cloud.

There is a search bar just below the visualization button. The search bar receives inputs
of books that was used to build the recommender system integrated in the application.
For examples, you can enter "Peter Pan" and then select the recommend button to print out a
list of books similar to Peter Pan.

The essence of the interface being divided into two was to enable a user analyze two 
different texts simultaneously. 
