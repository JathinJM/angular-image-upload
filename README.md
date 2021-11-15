# Picnic Web Assignment

# Steps to run the application

```
 - Installing packages and dependecies
    > npm install

 - Starting the Application
    > npm run start

    Application will run on port number 4200 and application access url will be "http://localhost:4200/"

 - Running the test cases

   > npm run test:app

   Above script will run the test cases.
```

# Technologies used and functionalities covered
 
 ```
For funationality: 
* Angular (version 12); 
* Typescript;
* NGRX (State Management);

For TDD:
* jest

Functionalities covered: 
* Fetching products list and product details from REST end points
* List of products is displayed using a responsive Grid with the following requirements:
    1. URL: /list
    2. Mobile device: 2 items per row 
    3. Tablet device: 3 items per row 4
    4. Desktop: 6 items per row
* Each product item contains the following information:
    1. Name
    2. Price
    3. Image
* The list of products can be filtered, by typing a query in a text field at the top of the list.
* A product container is a clickable / tappable element, which has the following logic:
    1. If the user is on mobile device, it redirects to a separate view with product details. 
        URL: /list/productID
    2. If the user is on desktop, it triggers a “popup/lightbox” view with product details.
* A User can also access product pages on the desktop directly by going to /list/productID

```
