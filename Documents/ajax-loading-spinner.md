# jQuery Ajax Loading Spinner Example
When make a request to server and while waiting for a response, we want to have a loading spinner that expresses this process.
The loading spinner is a gif icon or a icon that is created by CSS.
It's usually hang on center of screen whenever the request is sent to server and will be removed when the response is done.

## jQuery Ajax Loading Spinner Example
Follow the steps given below to create a loading.

### Create a file index.html
- Import jQuery library
- Create a button getDataBtn to request data
- Create a div richList to presents data
- Create a div loader to presents loading spinner

### Create a file style.css
- Style and hide div loader by default

### Create a file javascript.js
- Add click event to button getDataBtn
- When click on this button then make an Ajax call to api https://forbes400.herokuapp.com/api/forbes400?limit=400 to get data
- In Ajax, use function beforeSend to show div loader, this function will execute before a reponse is done
- In Ajax, use function complete to hide div loader, this function will execute after a response is done

# Conclusion
A loading spinner can be created by CSS or just simply is a gif icon.
It will be hang on between the screen when we make a request and a response is not done.
And to reach this, we need apply technologies: HTML, CSS, Javascript core/jQuery