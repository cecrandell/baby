# A Note from Caroline Crandell

"During my masters in computer science at University College London (UCL), I led a team of full-stack developers to build a mobile app in collaboration with Dr Iya Whiteley. I was responsible for developing the entire client website (hosted on Azure), enabling the client to upload new media to be rendered on the mobile app. I also developed the subscribe page on the mobile app, enabling users to sign up to the client’s mailing list. As this code now belongs to Dr Iya Whiteley after submitting this project in May 2021, I am not permitted to publish my code publically. As such, I have provided the `README` from the original (private) mobile app repository below. If you would like to see code snippets or see a live demonstration, please email me using my contact details at the bottom of this page. To view on the Google Play store, you can find more information [here](https://cosmicbabybooks.com/app-new)."

## Baby

[![YouTube](https://img.youtube.com/vi/fLU6xfHWmhw/0.jpg)](https://youtu.be/fLU6xfHWmhw)

**What does this application do and why?**

Our app features Dr Iya Whiteley’s research-informed black and white development images from Cosmic Baby Books. The app displays slideshows (with accompanying audio narration) to newborn babies in order to:

- Aid with the physiological development of their eyes and brain
- Calm them quickly
- Entertain and engage them
- Enable parents to take a break

![readme](public/assets/images/readme.png)

In the browser, the client is able to upload new images, audios, music and slideshows for users to view on the mobile app.

On the mobile app, users can:

- Sign up through an email form to hear updates about Cosmic Baby Books
- Adjust the audio and visual settings, based on the age of their baby
- Read about Dr Iya Whiteley and the science behind her work

**How the application is organised**

Newborn Baby App is divided into the following folders:

- backend - contains the code for the client website hosted on Azure
- public - contains the code for components and pages displayed on the mobile app
- src - contains the Ionic code which supports the mobile app
- build - contains the production code for the mobile app
- ios - contains the code for the mobile app for iOS devices (i.e., iPhone, iPad)
- android - contains the code for the mobile app for Android devices (i.e., Galaxy S5, Surface Duo)
- gitignore - instructs GitHub to omit any extraneous files, such as node modules

**Step-by-Step on how to run the application**

First clone this app repository to your computer. Open your terminal and navigate to where you would like to download the source code. Then for SSH, type:

```js
git clone git@github.com:cecrandell/baby.git
```

Or for HTTPS, type:

```js
git clone https://github.com/cecrandell/baby.git
```

Now that you have downloaded the app to your computer, navigate to the root folder and type:

```js
npm install
```

After installation, type in the terminal:

```js
ionic serve
```

In a few seconds, the mobile app will begin running in your default browser. Be sure to adjust the width of the browser to represent your preferred mobile device.

If you would like to install the mobile app directly onto your device, please do get in touch with the developers - our contact details are provided below.

**Technologies Used**

- Ionic
- Capacitor
- Cordova
- React.js
- Node.js
- Express
- mySQL
- mySQL Workbench
- REST API Routes
- HTML
- CSS
- Sass
- Typescript
- TSUN
- jQuery
- Axios
- Google Analytics
- Azure Containers
- Azure Blob Storage
- HTML Storage
- Launch image and icon implementation
- Postman
- XCode
- Android Studio
- Chrome DevTools

**Developers**

- Caroline Crandell - cecrandell - cecrandell19@gmail.com - [LinkedIn](https://www.linkedin.com/in/carolinecrandell/)
- Giuseppe Baldini - GiuseppeBaldini
- Chenuka Ratwatte - ucabcnd
