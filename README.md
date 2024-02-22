EcomVision is a web application that provides an interface to the user (Admin) for viewing Customers details and sales figures associated with the customer and their locations on map.

It provides a platform for the admin to view the sales dashboard. There is real time data being pulled from the backend. 
Dashboard where admin can view customer, sales, products and its reviews, geographical data and much more .

Admin can also user can view the details of the customers from the list and. He can also sort them to according to his/her needs and view the insights of whatever is happening in real time.
Dashboard has various components on the page including a general overview of all the other tabs and the data pulled from all those other tabs.

The product page has all the products loaded that have been injected into the mongo DB and with the help of mongo DB query the data is being pulled and displayed at the front end.

Map view uses Nivo-charts geo maps component to plot the regions based on the latitude and longitude data,
and markers marking the regions have an animation embedded and when clicked it shows the customers present on that map.
The application uses React as frontend hosted on NodeJS, API layer between client and the sink and MongoDB as it’s sink.
