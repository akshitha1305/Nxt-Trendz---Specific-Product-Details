<<<<<<< HEAD
Functionality to be added

autheticated prime user credentials(username: rahul, password:rahul@2021) authenticated non-prime user credentials(username: raja, password: raja@2021)
=======
# Nxt-Trendz---Specific-Product-Details

Functionality to be added

autheticated prime user credentials(username: rahul, password:rahul@2021)
authenticated non-prime user credentials(username: raja, password: raja@2021)
>>>>>>> 4b38b886e14e53f0b9e01f119e4049b7139bea51

The app must have the following functionalities

When an authenticated user opens the Products Route,

<<<<<<< HEAD
An HTTP GET request should be made to productsApiUrl with jwt_token in the Cookies and query parameters title_search, category, and rating with initial values as empty strings loader should be displayed while fetching the data After the data is fetched successfully, display the products list received in the response If the HTTP GET request made is unsuccessful, then the Failure view should be displayed When a non-empty value is provided in the Search Input and the Enter button is clicked Make an HTTP GET request to the productsApiUrl with jwt_token in the Cookies and query parameter title_search with value as the text provided in the Search Input loader should be displayed while fetching the data After the data is fetched successfully, display the products list received in the response When a Category is clicked Make an HTTP GET request to the URL productsApiUrl with jwt_token in the Cookies and query parameter category with value as the id of the category clicked loader should be
displayed while fetching the data After the data is fetched successfully, display the products list received in the response When a Rating is clicked Make an HTTP GET request to the URL productsApiUrl with jwt_token in the Cookies and query parameter rating with value as the id of the rating clicked loader should be displayed while fetching the data After the data is fetched successfully, display the products list received in the response When the Clear Filters button is clicked All the filters applied should be reset to initial values Make an HTTP GET request to the URL productsApiUrl withjwt_token in the Cookies and without any filters loader should be displayed while fetching the data After the data is fetched successfully, display the products list received in the response When multiple filters are applied, then the HTTP GET request should be made with all the filters that are applied

For example: When the Electronics Category is clicked and rating 4 and above is clicked the productsApiUrl will be as follows

JAVASCRIPT If the HTTP GET request returns empty products list, then No Products View should be displayed. If the HTTP GET request made is unsuccessful, then the Failure view should be displayed

When an unauthenticated user, tries to access the Product Item Details Route, then the page should be navigated to Login Route When an authenticated user clicks on a product in the Products Route, then the page should be navigated to Product Item Details route When an authenticated user opens the Product Item Details Route, An HTTP GET request should be made to productDetailsApiUrl with jwt_token in the Cookies and product id as path parameter loader should be displayed while fetching the data After the data is fetched successfully, display the product details and similar products received in the response Initially, the quantity of the product should be 1 The quantity of the product should be incremented by one when the plus icon is clicked The quantity of the product should be decremented by one when the minus icon is clicked If the HTTP GET request made is unsuccessful, then the Failure view should be displayed When the Continue Shopping button in the Failure view is clicked, then
the page should be navigated to Products Route API Requests & Responses

productDetailsApiUrl

API: https://apis.ccbp.in/products/:id Example: http://localhost:3000/products/16 Method: GET
=======
An HTTP GET request should be made to productsApiUrl with jwt_token in the Cookies and query parameters title_search, category, and rating with initial values as empty strings
loader should be displayed while fetching the data
After the data is fetched successfully, display the products list received in the response
If the HTTP GET request made is unsuccessful, then the Failure view should be displayed
When a non-empty value is provided in the Search Input and the Enter button is clicked
Make an HTTP GET request to the productsApiUrl with jwt_token in the Cookies and query parameter title_search with value as the text provided in the Search Input
loader should be displayed while fetching the data
After the data is fetched successfully, display the products list received in the response
When a Category is clicked
Make an HTTP GET request to the URL productsApiUrl with jwt_token in the Cookies and query parameter category with value as the id of the category clicked
loader should be displayed while fetching the data
After the data is fetched successfully, display the products list received in the response
When a Rating is clicked
Make an HTTP GET request to the URL productsApiUrl with jwt_token in the Cookies and query parameter rating with value as the id of the rating clicked
loader should be displayed while fetching the data
After the data is fetched successfully, display the products list received in the response
When the Clear Filters button is clicked
All the filters applied should be reset to initial values
Make an HTTP GET request to the URL productsApiUrl withjwt_token in the Cookies and without any filters
loader should be displayed while fetching the data
After the data is fetched successfully, display the products list received in the response
When multiple filters are applied, then the HTTP GET request should be made with all the filters that are applied

For example: When the Electronics Category is clicked and rating 4 and above is clicked the productsApiUrl will be as follows

JAVASCRIPT
If the HTTP GET request returns empty products list, then No Products View should be displayed.
If the HTTP GET request made is unsuccessful, then the Failure view should be displayed

When an unauthenticated user, tries to access the Product Item Details Route, then the page should be navigated to Login Route
When an authenticated user clicks on a product in the Products Route, then the page should be navigated to Product Item Details route
When an authenticated user opens the Product Item Details Route,
An HTTP GET request should be made to productDetailsApiUrl with jwt_token in the Cookies and product id as path parameter
loader should be displayed while fetching the data
After the data is fetched successfully, display the product details and similar products received in the response
Initially, the quantity of the product should be 1
The quantity of the product should be incremented by one when the plus icon is clicked
The quantity of the product should be decremented by one when the minus icon is clicked
If the HTTP GET request made is unsuccessful, then the Failure view should be displayed
When the Continue Shopping button in the Failure view is clicked, then the page should be navigated to Products Route
API Requests & Responses

productDetailsApiUrl

API: https://apis.ccbp.in/products/:id
Example: http://localhost:3000/products/16
Method: GET
>>>>>>> 4b38b886e14e53f0b9e01f119e4049b7139bea51
