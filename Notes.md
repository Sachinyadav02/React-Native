# ReactNative Notes

## Basic CMD 

- Create New Project CMD --> `npx react-native init ProjectName`  
- Run Project CMD --> `npm run android`

## First Program 

> App.js

``` reactnative
import React from 'react';
import {Button, Text, View} from 'react-native';

const App = () => {
  return (
    <View>
      <Text style={{color: 'red', fontSize: 30}}>React Native</Text>
    </View>
  );
};

export default App;
```

