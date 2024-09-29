# ReactNative Notes

## Basic CMD 

- **Create New Project CMD** --> `npx react-native init ProjectName`  
- **Run Project CMD** --> `npm run android`

## First Program 

> **App.js**

```js
import React from 'react';                
import {Text, View} from 'react-native';

const App = () => {
  return (
    <View>
      <Text style={{color: 'red', fontSize: 30}}>React Native</Text>
    </View>
  );
};

export default App;
```
## File Structure

## View , Text and Button

It is Component in ReactNative.

**(i) `View`** --> It is wrapper. Agar ek se jada code return liya to view ke andar wrap karna padega.  

**(i) `Text`** --> For any text.  

**(i) `Button`** --> For making Button.

```js
import React from 'react';                              // React ki core Library ko import kiya hai.
import {Button, Text, View} from 'react-native';        // Components ko use karne ke liye import karna padta hai

const App = () => {
  return (
    <View>
      <Text style={{color: 'red', fontSize: 30}}>React Native</Text>
      <Button title='Sachin'></Button>                                 // Title ke andar jo Button par Text chahiye vo likhate hai.
    </View>
  );
};

export default App;
```

## What is JSX ??

- JavaScript Extention ---> JavaScript ke andar hi HTML ka code Likhana pana.

**Example of JSX**

``` js
import React from 'react';                
import {Text, View} from 'react-native';

const name = "Sachin";
let age = 21;
var email = "mail4sachinyadav@gmail.com";

const App = () => {
  return (
    <View>
      <Text style={{color: 'red', fontSize: 30}}>(name)</Text>         // Output : Sachin
      <Text style={{color: 'red', fontSize: 30}}>(age)</Text>          // Output : 21
      <Text style={{color: 'red', fontSize: 30}}>(email)</Text>        // Output : mail4sachinyadav@gmail.com
      <Text style={{color: 'red', fontSize: 30}}>(age===25 ? "Above 18" : "Unknow age")</Text>        // Output : Above 18
    </View>
  );
};

export default App;
```






























