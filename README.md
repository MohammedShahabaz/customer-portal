Description:
Developed a single-page application in React and Typescript which shows a customer details
portal with the following specifications:
1. The portal has a list of customers on the left side and upon clicking a card on the left
the details of the customer are shown on the right side.
2. The customer list on the left can contain as many as 1000 entries.
3. The card in the list shows the name of the customer and his title.
4. Customer details include the customer name, title, address, and a 3x3 grid of 9
photos.
5. The selected card on the left is highlighted.


Getting started
Follow these steps to set up and run the project.
1. Used Virtualization with react-window
npm install react-window

2.created a mock API using a service like JSON Server 
For the Mock API Server:

Install JSON Server globally:
npm install -g json-server

Start the JSON Server:
json-server --watch db.json --port 5000
