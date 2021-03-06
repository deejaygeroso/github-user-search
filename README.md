# Github User Search
A simple page for searching user in github.

**Other Technologies Used:**  
[Redux](https://redux.js.org/) - for handling state management of the project and uses.  
[Redux Thunk](https://github.com/reduxjs/redux-thunk) - for handling redux side effect api calls.  
[Material UI](https://material-ui.com/) - for styling components.  
[Axios](https://github.com/axios/axios) - for REST api calls.  


## Application Folder & File Structure  

  ```js
    ...
      pages
      src
        actions
        modules
            search
               components
               containers
            user
               components
               containers
        reducers
        types
        store.js
      static
    ...
  ```
 
## Application Limitation Using Github Api.  
- Only the first 1000 search results are available when searching and paginating.  
- The app is not configured to use Basic Authentication or OAuth for github api so rate limit for API requests (based on originating IP address) allows for up to 60 requests per hour only.  
- The Search API, also rate limit allows you to make up to 10 requests per minute.  

## Application

You can view Live Application [here](http://ec2-18-223-119-153.us-east-2.compute.amazonaws.com).

**Development:** Installing and running the app on development:
```sh
npm install
npm run dev
```

**Production:** For building and running the app for production:

```sh
npm run build
npm run start
```

**ESlint:** 

```sh
npm run lint
```

**Test:** 

```sh
npm run test
```



