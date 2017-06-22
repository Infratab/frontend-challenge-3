# frontend-challenge-3

# Infratab Frontend Coding Challenge!

## Getting started
1. [Participate](#participate)
2. [Setup the project](#setup-the-project)
3. [Complete the Challenge!](#challenge)

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

### Setup the project
1. Change directory to report

#### Challenge

Your challenge is to implement the following designs given in the below section and fulfil the functional requirements listed below.You can implement the design using any js library/frameworks you like.

**NOTE:** Implement this task using plain html, css without any css frameworks and please implement the design as it is! (This doesn't hold you back from changing the text or messages in the app - feel free to change the english as you want)

### Functional requirements:

- Show list of items and "Your cart" sections as shown in the below image. If none of the items are added to your cart, show message in the "Your cart" section as shown in the below image.

   **NOTE:** Data for item list should be passed through json, do not directly hard code the data items in the html. 

   <img src='https://user-images.githubusercontent.com/13765124/27330493-404effba-55d7-11e7-83a8-5e84a55a8e5e.png' width=500 />


- User can add or remove items to Cart by clicking on Plus and Minus icons from both "Your cart" section and from the item itself. Price in the "Your cart" section changes dynamically as number of items changes.

- Show progress-bar above the "Your cart" section as shown in the below image. This progress bar will be filled up dynamically as the items added to/ removed from Cart, where 100% filled progress-bar indicates the Rs. 2000/-.

  **For example:**

  - If the total amount of your cart is Rs. 100/- then 5% of progress bar will be filled.
  - If the total amount of your cart is Rs. 450/- then 22.5% of progress bar will be filled.
  - If the total amount of your cart is more than Rs. 2000/- then 100% of progress-bar will be fiiled.
  
       <img src='https://user-images.githubusercontent.com/13765124/27329829-b5a97c2a-55d4-11e7-9b81-b3fc75095c4b.png' width=500 />
  
- Enable "Place order" button in Your cart section only if the ordered amount in >= Rs. 2000/-
         <img src='https://user-images.githubusercontent.com/13765124/27329922-1eaebe60-55d5-11e7-9563-08d9bbe6cf25.png' width=500 />


- On placing the order, show notification as shown in the below image
 
     <img src='https://user-images.githubusercontent.com/13765124/27330380-c503eb4a-55d6-11e7-9b2d-05b186657f66.png' width=500 />
     
     After showing the notification(i.e after successfully placing the order), set the app to initial state.
