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
    return ( 
      <CommunityList franchise="WeWork" />
    );
  }
} 
```

Screens would contain screen components that have to be insterted into the stack, in a react way. 
