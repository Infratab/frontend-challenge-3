# Infratab Frontend Coding Challenge!

## Getting started
1. [Participate](#participate)
2. [Complete the Challenge!](#challenge)

### Participate
There are two ways to participate in our coding challenge:
- [By cloning this repo and using the Github Flow](#cloning-the-repo-use-the-github-flow)
- [By downloading the entire project directory as a compressed folder](#downloading-the-project-directory)

We would like you to follow the Github flow to participate in the coding challenge if you are familiar with Git and its ecosystem. However, in case you are not familiar with Git, please feel free to download the project directory and then complete the [Challenge](#challenge)

#### Cloning the repo (Use the Github flow)
1. Clone this repository
2. Follow the [Github Flow](https://guides.github.com/introduction/flow/)
3. Complete the requirements listed in the [Challenge](#challenge)
4. Open a pull request!

#### Downloading the project directory
1. Download this project direactory as a compressed folder (`frontend-challenge.zip`)
2. Complete the requirements listed in the [Challenge](#challenge)
3. Email the compressed folder to careers@infratab.in or to the person with whom you have been interacting!

### Challenge

Your challenge is to implement the following designs given in the below section and fulfil the functional requirements listed below. Implement the design using any one of the **component based js frameworks**. Popular component based js frameworks are [React](https://facebook.github.io/react/), [Angular >= 2](https://angular.io/).. etc. Feel free to choose any other component based frameworks you are familiar with.

**NOTE:** 
1. Implement this task using plain html, css(sass, less) without any css frameworks (like: bootstrap, materialize)
2. Do not use any eCommerce frameworks which are already available. Example for such frameworks for react are [moltin](https://www.moltin.com/blog/2017/03/react-js/), [nicistore](https://github.com/yoonic/nicistore). Please do not use such frameworks.
3. Using css preprocessors like less, sass; task runners like grunt, gulp would plus point.
4. Please implement the design as it is! (This doesn't hold you back from changing the text or messages in the app - feel free to change the english as you want)

### Functional requirements:
- Show list of items and "Your cart" sections as shown in below image. If none of the items are added to your cart, show message in the "Your cart" section as shown in the below image.

   **NOTE:** Data for item list should be passed through json, do not directly hard code the data items in the html. 
   
   <img src='https://user-images.githubusercontent.com/23208209/27528104-6f9944f8-5a6c-11e7-8bf6-1b04f3d383a5.png' width=500 />


- User can add or remove the items to Cart by clicking on Plus and Minus icons from both "Your cart" section and from the item itself - price in the "Your cart" section changes dynamically as number of items changes.

- Show progress bar above the "Your cart" section as shown in the image. This progress bar will be filled up dynamically as the items added to/ removed from Cart, where 100% filled progress-bar indicates the Rs. 2000/-.

  **For example:**

  - If the total amount of your cart is Rs. 100/- then 5% of progress bar will be filled.
  - If the total amount of your cart is Rs. 450/- then 22.5% of progress bar will be filled.
  - If the total amount of your cart is more than Rs. 2000/- then 100% of progress-bar will be fiiled.
  <img src='https://user-images.githubusercontent.com/23208209/27528163-be85792e-5a6c-11e7-9bec-4834052cdce6.png' width=500 />
  
- User can change the currency either to Rupees or Dollar using the switch as shown in below the image. On the change of the currency, update the price to that currency in "Your cart" section(Set Rupees as default currency)
    <img src='https://user-images.githubusercontent.com/23208209/27528183-d658c240-5a6c-11e7-9003-566f2dd7bee0.png' width=500 />
 
- Enable checkout button only if the ordered amount is >= Rs. 2000/-.
   <img src='https://user-images.githubusercontent.com/23208209/27528216-fa1f61b6-5a6c-11e7-97c5-ce6881202706.png' width=500 />

- On click of "Checkout", show new page - which has form where user fills the name, email, phone number and pincode.
   <img src='https://user-images.githubusercontent.com/23208209/27528247-1f934034-5a6d-11e7-8e1a-72eebefadff4.png' width=500 />
   
   
 - Show the "Check" button beside to the pincode input field as shown in the image.On click of "Check" button make google api to get the address for that pincode and show the respose(address) in the text area.
   <img src='https://user-images.githubusercontent.com/23208209/27528266-38c3def6-5a6d-11e7-84e7-ec96299b9058.png' width=500 />
 
 
- On click of "Place order" button, navigate back to shopping page and show the notification as shown in the below image

   <img src='https://user-images.githubusercontent.com/23208209/27528278-5662d534-5a6d-11e7-9201-a16d949921c1.png' width=500 />
   
   After showing the notification(i.e after successfully placing the order), set the app to initial state.
