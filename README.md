# RnFuncComponent

# Step1 : Code Example
```
import React from 'react';
import { Text } from 'react-native';

const Cat = () => {
  return (
    <Text>Hello, I am your cat!</Text>
  );
}

export default Cat;
```
# Step2 : Image
![image](https://user-images.githubusercontent.com/108333173/183229605-c625203b-55ea-4ea6-b544-a823b3f941a3.png)



# Step3 : Explain
# 3.1 Import
```
import React from 'react';
import { Text } from 'react-native';
```
import các thư viện vào khi sử dụng


# 3.2 Function Component  
```
const Cat = () => {
  return ();
}
```
const Cat là tên function


= () nghĩa là gán biến Cat bằng 1 function dạng ES6 Function 
 
 
=>{
  return ();
}


nghĩa là function này return về 1 function component
# 3.3 Text
Text là 1 trong 6 core Component của ReactNative


5 Core còn lại là : Image,View,ScrollView,StyleSheet,TextInput


https://reactnative.dev/docs/components-and-apis#:~:text=Most%20apps%20will,to%20CSS%20stylesheets.
# 3.4 export default Cat
```
export default Cat;
```
Dùng để lấy biến mình vừa khai báo trong file này và import vào file khác để sử dụng giống phần #2.1 Import
