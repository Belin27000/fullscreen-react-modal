<h1 align="center">Welcome to fullscreenreact-modal 👋</h1>
<p>
  <a href="https://www.npmjs.com/package/fullscreenreact-modal" target="_blank">
    <img alt="Version" src="https://img.shields.io/npm/v/fullscreenreact-modal.svg">
  </a>
  <a href="https://github.com/Belin27000/fullscreen-react-modal#readme" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/Belin27000/fullscreen-react-modal/graphs/commit-activity" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" />
  </a>
  <a href="https://github.com/Belin27000/fullscreen-react-modal/blob/master/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/github/license/Belin27000/fullscreenreact-modal" />
  </a>
</p>

fullScreen react modal which can be configured with the text you want and picture

## How to use it

### 1-Install

```sh
npm i fullscreenreact-modal
```

### 2-Import `FullScreenModal` (you can name it as you want)

 - import `FullScreenModal` from 'fullscreenreact-modal'

### 3-Use it (you can name it as you want)
 
 Mandatory: 
   - you have to pass boolean value to: isActive={`showModal`}
   - `handleCloseModal` is the function which close the modal you can use your own code

   ```js
   const [showModal, setShowModal] = useState(false);
   const handleCloseModal = () => {
        setShowModal(false);
    };
   ```

 ```js
   return(
    ... your code ... 
   <FullScreenModal isActive={showModal} text="whatever you want" imgPath='image path or can be empty' onClose={handleCloseModal} />
   ),
```




## Author

👤 **Yann LECERF**

* Website: https://conseilsandtechs.com/
* Github: [@Belin27000](https://github.com/Belin27000)

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2023 [Yann LECERF](https://github.com/Belin27000).<br />
This project is [MIT](https://github.com/Belin27000/fullscreen-react-modal/blob/master/LICENSE) licensed.

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_