https://sudarshan34.github.io/ImageApp/

I have defined  Unsplash API access key as accessKey.
and selected various HTML elements using document.getElementById and stored them in variables and also defined two variables: inputData to store the user's search input and page to keep track of the current page.
The searchImages function is an asynchronous function that handles the image search. It constructs the API URL with the user's search query and access key,
then fetches data from the Unsplash API using the fetch function.When the API data is received, it's parsed as JSON, and the existing search results are cleared if it's the first page of results.
The function iterates through the results, creating a div element for each image and adding an image and a link to the image's Unsplash page.The images are appended to the searchResultsbtn (which is a container for the search results).The page variable is incremented to prepare for the next page of results.If page is greater than 1, the "Show More" button is displayed.
Event listeners are set up to handle form submissions and "Show More" button clicks, calling the searchImages function accordingly.



