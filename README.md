# Object-Relational Mapping: E-Commerce Back End
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 
  ![Profile View Counter](https://komarev.com/ghpvc/?username=uknity) 
  ![](https://img.shields.io/badge/GitHub-uknity-181717?style=for-the-badge&logo=github)  
  ![Your Repository's Stats](https://github-readme-stats.vercel.app/api?username=uknity&show_icons=true) 
  ![Your Repository's Stats](https://github-readme-stats.vercel.app/api/top-langs/?username=uknity&theme=blue-green)    
  
_____________________________________________________  

## Table of Contents
  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Credits](#credits)
  - [Test](#test)
  - [Questions](#questions)
  - [License](#license)
______________________________________________________
![image](https://user-images.githubusercontent.com/77338531/116001297-c78b5300-a5c1-11eb-8b0e-22171201d40c.png)

GitHub Project URL: https://github.com/uknity/E_Commerce_Back_End
Video Demonstration Part 1: https://drive.google.com/file/d/1zXOWN-fUtU8sx-dPFoTgSR6efhHtPATW/view  
Video Demonstration Part 2: https://drive.google.com/file/d/1ywLu8iwp20FMrrMiVXeZswZRqBQmHZRa/view  
## Description

This project allows e-commerce clients an easy and efficient way to access, display, update, and delete product categories, products, and product tags.

## Installation

To install:  
1.  Open the package.json file in the terminal.  Type "npm install" to activate the npm dependencies.  
2.  Open server.js in the terminal.  Type, "node seeds/index.js" to seed the database.  
3.  Type, "node server.js" on the command line to initiate the server.  
4. Open Insomnia and type "localhost:3001/api/categories/" to view the product categories in the database.  

## Usage
### View All
To view all categories, products, or tags, respectfully, type "localhost:3001/api/categories/", "localhost:3001/api/products/", "localhost:3001/api/tags/" and send a GET request.  
### View by Id
To view by id, enter the id after the final forward slash.  \(e.g. "localhost:3001/api/category/1"\)  

### Update Category
To update a category, add the category id to the end of the URL in Insomnia.  Enter the updated category name as follows into Insomnia:  
{
	"category_name": "Alpaca Yarn"
}  
Send a PUT request.  
### Update Product
To update a product, add the product id to the end of the URL in Insomnia.  Enter the updated product information as follows into Insomnia:  
{
      "product_name": "Basketball",
      "price": 40.00,
      "stock": 10,
      "tagIds": [1, 2, 3, 4]
}  
Send a PUT request.  
### Update Tag
To update a tag, add the tag id to the end of the URL in Insomnia.  Enter the updated tag name as follows into Insomnia:  
{
	"tag_name": "craft"
}
Send a PUT request. 
### Create Category/Product/Tag
Type in either categories/, products/, or tags/ (depending on what you are creating) at the end of the URL in Insomnia.  Enter the new category/product/tag data as formatted in the update section.  Send a POST request.
### Delete Category/Product/Tag
Type in the id of the category/product/tag you are deleting at the end of the path URL.  (eg. "localhost:3001/api/categories/2").  Send a DELETE request.

## Credits

This project was created with the assistance of the amazing staff and students of the Georgia Tech Coding Boot Camp.

## Test

To test, please run the installation and instructions exercises.  You may view the database in MySQL Workbench to ensure that the database is being updated effectively.  

## Questions

For additional information, please visit my GitHub site or send me an email at the address below.  
  
GitHub Username: uknity  
GitHub Link: https://github.com/uknity  
Email Address: uknity@gmail.com  

## License

https://opensource.org/licenses/MIT