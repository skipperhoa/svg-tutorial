## Android and iOS App Development Using React Native
Please Like, Share, and Subscribe if you like the video : 

👉 [Creator's Channel](https://www.youtube.com/channel/UCBOZRctXJSg9YNLyddedASg?sub_confirmation=1)

## List of  Project App Mobile
- App Mobile 🚀 : 👉 [Project 1 app mobile](https://github.com/skipperhoa/Android-and-iOS-App-Development-Using-React-Native/tree/project1-mobile)
- MyFirstApp - React Native with Expo 🚀 : 👉 [Project 2 app mobile](https://github.com/skipperhoa/Android-and-iOS-App-Development-Using-React-Native/tree/project2-mobile)


Nếu bạn thấy thú vị, thì đăng ký kênh ủng hộ tôi (If you find it interesting, then subscribe to my channel to support me)
- YouTube Channel: [Creator's Channel](https://www.youtube.com/channel/UCBOZRctXJSg9YNLyddedASg?sub_confirmation=1)
- TikTok: [@ha.nguyn.coder](https://www.tiktok.com/@ha.nguyn.coder)
- Twitter: [@skipperhoa](https://x.com/skipperhoa)
- Facebook Fanpage: [Fanpage](https://www.facebook.com/profile.php?id=100049475056780)
- Website: [hoanguyenit.com](https://hoanguyenit.com)

# Demo
![hoanguyenit.com](https://github.com/skipperhoa/svg-tutorial/blob/river/river.jpg)

# React

```
import * as React from "react";
const SVGComponent = (props) => (
  <svg
    xmlns="http://www.w3.org/2000/svg"
    width={400}
    height={400}
    viewBox="0 0 124 124"
    fill="none"
    {...props}
  >
    <defs>
      <linearGradient id="grad1" x1="0%" x2="100%" y1="0%" y2="0%">
        <stop offset="0%" stopColor="yellow" />
        <stop offset="100%" stopColor="red" />
      </linearGradient>
    </defs>
    <path
      d="M 0 0 L 0 100 C 20 100 0 70 30 70 S 40 60 40 40 S 50 30 65 15 S 70 0 70 0 Z"
      stroke="trnsparent"
      fill="url(#grad1)"
    />
  </svg>
);
export default SVGComponent;
```

# React Native 

```
import * as React from "react";
import Svg, { Defs, LinearGradient, Stop, Path } from "react-native-svg";
const SVGComponent = (props) => (
  <Svg
    xmlns="http://www.w3.org/2000/svg"
    width={400}
    height={400}
    viewBox="0 0 124 124"
    fill="none"
    {...props}
  >
    <Defs>
      <LinearGradient id="grad1" x1="0%" x2="100%" y1="0%" y2="0%">
        <Stop offset="0%" stopColor="yellow" />
        <Stop offset="100%" stopColor="red" />
      </LinearGradient>
    </Defs>
    <Path
      d="M 0 0 L 0 100 C 20 100 0 70 30 70 S 40 60 40 40 S 50 30 65 15 S 70 0 70 0 Z"
      stroke="trnsparent"
      fill="url(#grad1)"
    />
  </Svg>
);
export default SVGComponent;
```

# SVG
```
<svg xmlns="http://www.w3.org/2000/svg" width="400" height="400" viewBox="0 0 124 124" fill="none">
   <defs>
            <linearGradient id="grad1" x1="0%" x2="100%" y1="0%" y2="0%">
                <stop offset="0%" stop-color="yellow" />
                <stop offset="100%" stop-color="red" />
            </linearGradient>
        </defs>

 <path d="M 0 0 L 0 100 C 20 100 0 70 30 70 S 40 60 40 40 S 50 30 65 15 S 70 0 70 0 Z"
         stroke="trnsparent" fill="url(#grad1)"/>
</svg>
```
