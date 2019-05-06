[![JSHeroes React-Native-Community](https://img.shields.io/badge/JSHeroes-React--Native--Community-blue.svg)](https://github.com/jsheroes/react-native-community/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

# Getting Started

React-Native allows you to write mobile apps (Android and iOS) using React and JavaScript. Here we compiled some resources and info which can help with your first steps with React-Native.

## Resources

The main docs are a great resource: https://facebook.github.io/react-native/docs/getting-started.html
- you'll need to follow one of the instalation guides - using `expo` or building native code - in order to start playing around/working on a react native app;
- if you're just getting started/looking to learn, we recommend starting with `expo` in order to have everything up and running much quicker.

Another excellent resource that comes with a lot of interactive examples is http://www.reactnativeexpress.com/.

For those who prefer video tutorials: https://egghead.io/lessons/react-start-building-a-react-native-application.

## Writing your first React-Native Component

Components are the building block of any UI. React Native manages the mapping from JavaScript components to the native UI which is actually rendered.

If you've worked with React.js, you will find React-Native components familiar.

### Examples
```js
import React, { Component } from 'react'
import { AppRegistry, View, Text, StyleSheet } from 'react-native'

export default class App extends Component {
  render() {
    return (
      <View style={styles.container}>
        <Text style={styles.text}>Hello World!</Text>
      </View>
    )
  }
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    justifyContent: 'center',
    alignItems: 'center',
  },
  text: {
    backgroundColor: 'whitesmoke',
    color: '#4A90E2',
    fontSize: 24,
    padding: 10,
  },
})

AppRegistry.registerComponent('App', () => App)
```

## Testing React-Native Components

### Examples
`to be added`
