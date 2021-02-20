# **React Native Documentation** 
<div>
    <img src="./pictures/React-Native-Titre.png"/>
</div>

<br/>

## **1. Setup Development : NodeJS, React Native CLI, Android Studio, Setup Global Enviroment…**
**[click here](https://medium.com/@prasadjivane/react-native-environment-setup-on-windows-10-47a3b5e833b9)**

<br/>

## **2. Overview of React Components: Stateful Component – Stateless Component**
<div>
    <p>Core APIs React Native : Text,View,StyleSheet,Components,FlatList<p>
    <img src="./pictures/Picture1.png"/>
    <img src="./pictures/Picture3.png"/>
</div>
<div>
    <p>Câu hỏi: <p>
    <img src="./pictures/Picture2.png"/>
</div>

***

### ***JSX là gì?***
```javascript
    const element = <h1>Codingwithvudang</h1>;
```

Cú pháp thẻ này không phải là một chuỗi kí tự cũng không phải là một thẻ HTML

Nó được gọi là JSX, là một cú pháp mở rộng cho JavaScript. Chúng tôi khuyến khích sử dụng JSX với React để mô tả giao diện (UI). JSX có thể trông giống Ngôn ngữ Khuôn mẫu (Template language), nhưng JSX đi kèm với toàn bộ tính năng của JavaScript.

<div>
    <img src="./pictures/Picture4.png"/>
</div>

#### **Bài tập JSX:**
<div>
    <img src="./pictures/Picture5.png"/>
</div>

***

### ***FlatList:***
<div>
    <img src="./pictures/Picture6.png"/>
</div>

> Chú ý về keyExtractor, Data Source và Render Method.

<div>
    <img src="./pictures/Picture7.png"/>
</div>

> Item trong list phải có Unique ID

<div>
    <img src="./pictures/Picture8.png"/>
</div>

#### **Bài tập FlatList:**
<div>
    <img src="./pictures/Picture9.png"/>
</div>

<br/>

## **3. Navigation & Button – Building Resusable Component**
### **1. Button Types**
<div>
    <img src="./pictures/Picture10.png"/>
</div>

```javascript
<Button title='login' onPress={()=> doSomeThing()}/>

<TouchableOpacity onPress={()=> doSomeThing()}>
    <Text>click</Text>
</TouchableOpacity>
```

***

### **2. Navigation**
**[click here](https://reactnavigation.org/docs/4.x/getting-started/)**

* Demo cho học viên cách dùng StackNavigator
* Props trong React Native
* Giới thiệu về Destructuring trong ES6

#### **Bài tập:**
Tạo 1 Project mới có 3 Screen: **ImageScreen**, **SignupScreen**, **LoginScreen**. Với logic như sau: Khi app được render screen đầu tiên hiển thị là LoginScreen, 1 Button đăng nhập – 1 Button nếu chưa có tài khoản thì đăng kí, 1 button Chuyển tới ImageScreen.

***

### **3. Reuseable Component**
<div>
    <img src="./pictures/Picture11.png"/>
</div>

* Tạo component ImageDetail,ImageScreen dùng FlatList để render ra list hình ảnh kèm Caption.
* Giải thích về Parent To Child và their Communicating thông qua PROPS
* Render Image: <Image source={require(‘Source Image’)}/>

#### **Bài tập:**
<div>
    <img src="./pictures/Picture12.png"/>
</div>

<br/>

## **4. State Management in React Components**
### ***Props vs State***
<div>
    <img src="./pictures/Picture13.png"/>
</div>



