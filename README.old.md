# ecommerce.six

Building an ecommerce site using React.js and Material-UI.
1-Setup: 1. npx create-react-app . in order to create the starter file/folder structure 2. delete src folder/files 3. make a new src folder and create a App.js and index.js file in the folder

2-Mock Products 1. create a component folder 2. create a Products folder in the component folder 3. In the Products folder create a Product folder, a style.js file and a Products.jsx file
a. Products.jsx file: import Grid from material-ui/core
Use Grid component justify="center" and give it spacing of {4}
b. Make a const products [array] with two {objects that has the name, id, and description of the two products}
c. In the Grid component add the products array and use a map((product) => (<Grid><Product /></Grid>)) function with an anonymous function inside of it that points to a <Grid> component that has the <Product> component inside of it 4. In the Product folder create a style.js file and a Product.jsx file
a. In the Product.jsx file import {Card, CardMedia, CardContent, CardActions, Typography, IconButton } from '@material-ui/core'
b. Then import { AddShoppingCart } from '@material-ui/icons'
this will add the image of the cart in the upper right.
c. return (<Card></Card> components) to the Products.jsx file
3-Navbar,
4-Commerce Products,
5-Add to Cart,
6-Cart Layout
