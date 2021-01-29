# my-app-routing
1. Create a new route that renders the <Welcome/> component.
   1) The URL path should be /welcome/:name. :name represents dynamic data passed in via the URL.
      a) This data gets added to a match.params object that is passed as a prop to the component the Route renders.
      b) You would access the route with a URL like /welcome/davey. You can access the variable with props.match.params.name within the component.
   2) If the <Welcome/> component is accessed through this URL, it should display the dynamic name from the URL.
   3) If the <Welcome/> component is accessed through "/" route, it should maintain its original behavior and display the value passed in with the "name" prop.
2. Update the Router functionality to show a 404 component when there is no matching route for the URL specified
