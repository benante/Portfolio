Based on the <a href="https://github.com/benante/cineCloud">CineCloud project</a>

## 1. Write code that executes asynchronously
The code includes the usage of ```async``` and ```await``` keywords in several functions, such as ```fetchPopularMovies()```, ```extraDetails()```, ```revenueChart()```, and ```movieAPIFetch()```. This indicates that these functions perform asynchronous operations.
For example, the ```fetchPopularMovies()``` function is declared as ```async``` and uses ```await``` when calling the ```movieAPIFetch()``` function, indicating that it waits for the asynchronous ```fetch``` operation to complete before proceeding.

![image](https://github.com/benante/Portfolio/assets/63957194/200fec60-3bfa-48f0-9c1b-a5405427215c)


## 2. Use callbacks to access values that aren’t available synchronously

## 3. Use promises to access values that aren’t available synchronously
Promises are used in the ```movieAPIFetch()``` function to handle asynchronous operations and fetch data from the TMDB API.
The ```fetch()``` method returns a promise that is resolved with the response data when it is available. The code uses ```.then()``` to handle the resolved promise and .catch() to handle any errors.

![image](https://github.com/benante/Portfolio/assets/63957194/0fff6a70-ba05-419d-be33-95e60e7b1c7f)

<img src="https://github.com/benante/Portfolio/assets/63957194/79bdfa42-c6b5-4d64-a68d-ca119fea6b88" height="300"/ >

## 4. Use the fetch method to make HTTP requests and receive responses

![image](https://github.com/benante/Portfolio/assets/63957194/536d0e47-474c-4d44-86b8-ea89d96d66be)


## 5. Configure the options argument of the fetch method to make GET and POST requests
The ```movieAPIFetch()``` function uses the ```queryOptions``` object to configure the ```headers``` for the fetch request. It includes the ```Authorization``` header to provide the API key for authentication

The ```queryOptions``` object is passed as the second argument to the ```fetch()``` method to set the headers for the request

![image](https://github.com/benante/Portfolio/assets/63957194/7aa91d71-444d-4e31-bd0e-b3c1e05c4e83)

![image](https://github.com/benante/Portfolio/assets/63957194/cd76f544-627e-4f97-b247-efd7ff03866e)


## 6. Use the map array method to create a new array containing new values
The ```map()``` method is used in the ```extraDetails()``` function to iterate over an array of movie details ```castArray``` and create a new array ```movieList``` containing formatted HTML elements.

Each element in ```castArray``` is transformed into an HTML list item using template literals and the ```map()``` method. The resulting array is then joined with an empty string to form a single HTML string.

![image](https://github.com/benante/Portfolio/assets/63957194/86f07d44-90bb-44ed-8fa3-104aea019042)


## 7. Use the filter array method to create a new array with certain values removed

## 8. Access DOM nodes using a variety of selectors

Some elements are declared at the beginning of the ```script.js``` file using ```querySelector```, that targets ```tag```, ```class``` and ```id``` elements.
![image](https://github.com/benante/Portfolio/assets/63957194/3ad8bc77-8b56-4cd4-a58c-80c336e99df5)

```getElementById``` and ```getElementsByClassName``` are also used to retrieve specific element of the DOM

![image](https://github.com/benante/Portfolio/assets/63957194/b89c06ab-4261-4950-97c9-082aac43d7ed)


![image](https://github.com/benante/Portfolio/assets/63957194/4bae74a2-0a7b-4c85-bda1-de90ceb0804c)


## 9. Add and remove DOM nodes to change the content on the page
DOM nodes are added or removed whenever the ```<button>``` element is clicked

![image](https://github.com/benante/Portfolio/assets/63957194/f0e55240-2c22-4720-a2dc-4fe37634dea7)


## 10. Toggle the classes applied to DOM nodes to change their CSS properties

## 11. Use consistent layout and spacing

![image](https://github.com/benante/Portfolio/assets/63957194/0d079dd3-56b3-40c2-bb14-94c1588b9fcb)


## 12. Follow a spacing guideline to give our app a consistent feel

## 13. Debug client side JS in our web browser

```console.log(err)``` is used in the ```movieAPIFetch()``` function to log any errors that occur during the fetch operation

![image](https://github.com/benante/Portfolio/assets/63957194/b2fe8a58-c9a7-43e7-ba5e-82f5d4598c86)


## 14. Use console.log() to help us debug our code
Use of ```console.log()``` is always fundamental for debugging. Usually it does get removed from the code once we are certain that everything runs correctly
