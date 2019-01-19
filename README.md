# react-communify
Use these fat data-driven UI components to publish communify-content onto your website

# Install 
`yarn add react-communify`

# Example

```js
import React from "react";
import { CommunityList, EventsList, JobList, MentorList, StartupList, screens } from "react-communify";

class Home extends React.Component {

  render(){
    const city = this.props.query.city;
    return ( 
      <CommunityList franchise="WeWork" city={city} />
    );
  }
} 
```

Screens would contain screen components that have to be insterted into the stack, in a react way. 


# Props

* endpoint?: server endpoint
* token?: api access token
* style?: different UI style, e.g. list/grid or theme

**variables:**
* franchise
* city
* ???
