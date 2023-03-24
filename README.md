Display Current Date and Time
This is a simple HTML file that displays the current date and time when a button is clicked.

How to Use
To use this code, simply open the index.html file in a web browser. Click the "Display Date and Time" button to see the current date and time displayed below the button.

Code Explanation
The index.html file contains the HTML code for the button and the script that displays the date and time. The button is created using the <button> tag with an onclick attribute that calls the displayDateTime() function when clicked.

The displayDateTime() function uses the Date object to obtain the current date and time, and the toLocaleString() method to convert it to a human-readable format. The date and time is then displayed in a <p> element with an id of "datetime" using the innerHTML property of the document.getElementById() method.


License
This code is licensed under the MIT License. See the LICENSE file for details.
