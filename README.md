# React Practice - Image Uploading

React practice following a YouTube tutorial.

---

### Tutorial I followed:

- ##### Video: [React Image Upload Made Easy - Academind](https://www.youtube.com/watch?v=XeiOnkEI7XI)

- ##### Article: [React.js Image Upload](https://academind.com/learn/react/snippets/image-upload/)

- **Ellie's note**: This project is currently incomplete. Need to watch another tutorial to create an API for image storage ([Firebase Cloud Functions - Creating a REST Endpoint with Cloud Functions](https://www.youtube.com/watch?v=qZ1EFnFOGvE)) or find an alternative.

---

### Steps:

1. Create an react app using 'create-react-app'
2. Go to 'app.js'

- Change app from functional component to class (remember to import Component from React)
- Start writing code (all in app.js)

3. Install Axios

4. At this point, I'm missing an api endpoint that I can post the image to:

```javascript
axios.post("{url}", fd, {
  //need to provide a correct {url} here
  onUploadProgress: progressEvent => {
    console.log(
      "Upload Progress: " +
        Math.round((progressEvent.loaded / progressEvent.total) * 100) +
        "%"
    );
  }
});
```

---

### Dependencies:

- Axios (https://www.npmjs.com/package/axios): Promise based HTTP client for the browser and node.js
