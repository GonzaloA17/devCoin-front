# DevCoin API 🏛️💰💱

https://dev-coin.web.app/

A fullstack JS crypto exchange app for the web.

### Backend Repository

https://github.com/JRobuschi/DEVCOIN

### Used technologies

| Tool            | Used to                                                                     |
| --------------- | --------------------------------------------------------------------------- |
| ✅ React   | Creating the UI with state based components   |
| ✅ TailwindCSS   | Style the components based on utility-first classes      |
| ✅ Firebase       | Upload and retrieve profile pictures              |
| ✅ Axios     | HTTP requests  |
| ✅ Browser Image Compression   | Compressing images before uploading                                          |
| ✅ Chart.JS      | Display cryptocurrencies data inside a chart                                                          |
| ✅ Moment.JS         | Date formatting                                                      |
| ✅ ReactRouterDom       | Routing and navigating the app |
| ✅ react-toastify          | Display toasts notifications to provide user feedback       |
| ✅ socket.IO | Stablishing and mantaingin a conneciton to a web socket for real time notifications   |

### Features

- Creating and verifing an account.
- Buying and selling cryptocurrencies.
- Transfering crypto among users.
- Light/Dark mode
- Personalize user data (change name/lastName/profilePicture/password)


### Global State Management

In order to manage global state without adding any extra dependencies, the app makes use of the ContextAPI.
First, the App component (the higher level one) fetchs all the necessary data and sets several states:

![Screenshot_5](https://user-images.githubusercontent.com/102425176/216169921-62dec5f8-fbad-4608-a1da-72486357aaf7.png)

Then, two objects are created holding these states: sessionData and coinsData, the first one keeps the user session data, such as the username, the unique hexacode used for sending transactions and so. The second one holds all data related to the current prices of different cryptos (provided by coinGECKO) and the unique wallet of the logged user. The objects are passed as values of the context Providers.
![Screenshot_6](https://user-images.githubusercontent.com/102425176/216168385-d5406d71-f20a-4dcb-bed3-46eb52ccdc52.png)

In order to make use of the context, we took advantage of the destructuring syntax of javascript.


![Screenshot_7](https://user-images.githubusercontent.com/102425176/216168761-9135682b-5c2e-4cdc-b0a2-9e5d4edd5bb2.png)


### Styling and Responsiveness

The app's design system is based on TailwindCSS, it's fully responsive and should render properly on all devices.



### Contact Us
<img src="https://camo.githubusercontent.com/7e1a1a039c75a7c4d2a91d7f97bf0a1c2adcf7cb49b7dbbfc02963a4f9fdaca4/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c696e6b6564696e2d2532333030373742352e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6c696e6b6564696e266c6f676f436f6c6f723d7768697465" alt="Linkedin" data-canonical-src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" style="max-width: 100%;">
<a href="https://www.linkedin.com/in/juan-cruz-robuschi/"><u>Robuschi Juan Cruz<u><a><br>
<a href="https://www.linkedin.com/in/victor-maximiliano-herrera/"><u>Herrera Victor Maximiliano<u>
</a><br>
