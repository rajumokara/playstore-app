In this project, let's build an **App Store** 

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/app-store-output.gif" alt="app store output" style="max-width:90%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>





### Set Up Instructions


<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`


### Completion Instructions


<br/>

The app must have the following functionalities

- Initially, the **Social** tab should be active and the apps with **Social** as their category should be displayed
- When a value is provided in the search input
  - The apps in the active category, that include search input value in their name should be displayed
  - When another tab is clicked, the apps in the corresponding category, that include search input value in their name should be displayed
  - The search should be case insensitive
- When the search input is empty,
  - All the apps in the active category should be displayed
  - When another tab is clicked, the apps in the corresponding category should be displayed
- The `AppStore` component is provided with `tabsList`. It consists of a list of tabItem objects with the following properties in each tabItem object

  |     Key     | Data Type |
  | :---------: | :-------: |
  |    tabId    |  String   |
  | displayText |  String   |

- The `AppStore` component is provided with `appsList`. It consists of a list of app objects with the following properties in each app object

  |   Key    | Data Type |
  | :------: | :-------: |
  |  appId   |  Number   |
  | appName  |  String   |
  | imageUrl |  String   |
  | category |  String   |

</details>


<summary>Components Structure</summary>

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/app-store-component-structure-breakdown.png" alt="app store component structure breakdown" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>




<summary>Implementation Files</summary>
<br/>

Use these files to complete the implementation:

- `src/components/AppStore/index.js`
- `src/components/AppStore/index.css`
- `src/components/TabItem/index.js`
- `src/components/TabItem/index.css`
- `src/components/AppItem/index.js`
- `src/components/AppItem/index.css`






