# my-app-routing
1. Create a new route that renders the <Welcome/> component.
   a. The URL path should be /welcome/:name. :name represents dynamic data passed in via the URL.
      1) This data gets added to a match.params object that is passed as a prop to the component the Route renders.
      2) You would access the route with a URL like /welcome/davey. You can access the variable with props.match.params.name within the component.
   b. If the <Welcome/> component is accessed through this URL, it should display the dynamic name from the URL.
   c. If the <Welcome/> component is accessed through "/" route, it should maintain its original behavior and display the value passed in with the "name" prop.
2. Update the Router functionality to show a 404 component when there is no matching route for the URL specified
