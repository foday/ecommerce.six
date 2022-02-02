# ecommerce.six

Building an ecommerce site using React.js and Material-UI.
1-Setup: 1. npx create-react-app . in order to create the starter file/folder structure 2. delete src folder/files 3. make a new src folder and create a App.js and index.js file in the folder

2-Mock Products 1. create a component folder 2. create a Products folder in the component folder 3. In the Products folder create a Product folder, a style.js file and a Products.jsx file
a. Products.jsx file: import Grid from material-ui/core
Going to type products.map and in the map() function we get each (product) => (we want to return something specific) which is a <Grid of type item with a key={product.id}> everytime you are looking through something with jsx using map() you want to use a {product.id} inside the Grid we add xs={12} which means full width in mobile devices for small devices it will take 6 spaces sm={6} which will mean two columns, for medium 4 md={4} for large we will do 3 lg={3}
b. In the Grid component we put <Product /> component, also you need to import the <Product/>.  
Use Grid component justify="center" and give it spacing of {4}
c. Make a const products [array] with two {objects that has the name, id, and description of the two products}
d. In the Grid component add the products array and use a map((product) => (<Grid><Product /></Grid>)) function with an anonymous function inside of it that points to a <Grid> component that has the <Product> component inside of it 4. In the Product folder create a style.js file and a Product.jsx file
a. In the Product.jsx file import {Card, CardMedia, CardContent, CardActions, Typography, IconButton } from '@material-ui/core'
b. Then import { AddShoppingCart } from '@material-ui/icons'
this will add the image of the cart in the upper right.
c. return (<Card></Card> components) to the Products.jsx file

3-Navbar
    import { AppBar, Toolbar, IconButton, Badge, MenuItem, Menu Typography}
    from material-ui/core 
    Then import { ShoppingCart } icon from material-ui/icons
    <AppBar in a fixed position, with a color that = inherit and in a {class style called appBar}>
    <Toolbar> component is used and between the <Toolbar> is <Typography>
4-Commerce Products,
5-Add to Cart,
6-Cart Layout
