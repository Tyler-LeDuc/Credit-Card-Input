# Credit Card Input for React Native

<p align="center">
<img src="https://github.com/Tyler-LeDuc/Credit-Card-Input/blob/master/preview-ios.gif?raw=true" width=200/>
</p>

Code:

```js
<CreditCardInput onChange={this._onChange} />
// or
<LiteCreditCardInput onChange={this._onChange} />
```


# Features
* Stylish and intuitive design for users to input credit card info
* Scale the Credit Card for smaller screens
* Lite version for smaller screens
* Credit-card input validations, formatting, and privacy while you're typing
* Supports Android and iOS

# How to use

```bash
npm i --save react-native-credit-card-input
```

Add these lines to your react-native code

```js
import { CreditCardInput, LiteCreditCardInput } from "react-native-credit-card-input";

<CreditCardInput onChange={this._onChange} />

```