# Backend Engineer Test | take home coding challenge guidelines.
Please organize, design, test, document, and deploy your code as if it were going into production.

## Challenge Description

***Write a program that can price a cart of books from different cities in Indonesia, accept multiple books and display a total detailed invoice as well.***

***You must use integrate with API raja ongkir : http://api.rajaongkir.com/dokumentasi/starter***

***Category Table***
| Id | Code | Name | Description |
| -------- | -------- | -------- |  -------- | 
| 1 | TR1234 | Fiction | Sciene Fiction |

***Book Table***
| Id | Category Id | Title | Author | Description | Price
| -------- | -------- | -------- |  -------- | -------- |  -------- | 
| 1 | 1 | Harry Potter | J.K Rowling | Magic | 25.000

## Requirements
1. Write the program using the programming language or **FRAMEWORK** you are good at.
1. Using Authenication(Login & Register).
1. Stick to Object Oriented fundamentals in all aspects of your code. 
1. Stick to SOLID principles.
1. Dockerize your project.
1. Use pre-defined [Design Patterns](https://en.wikipedia.org/wiki/Software_design_pattern) whenever needed in your code. 
1. Input should be via either (whatever suits you)
	1. The command line in the form `createCart --product='T-shirt' --product='Blouse' --product='Pants' --product='Shoes' --product='Jacket'`.
	1. **Or** a simple REST API.
1. Write unit tests to cover your core code fully.
  
## Expected Deliverables
1. Hosted repository for the program, link to it with Github. **Reply** with the repo link to the **email** (galuh@semestaenergi.co.id darmawan.salihun@semestaenergi.co.id Suryo.prakoso@semestaenergi.co.id).
1. Code should be well structured, suitably commented, have error handling, and be tested.
1. README file, where you describe your solution (design and architecture), how to run the program. You can use pseudo-code here.

 
### How will we review?
[Guidelines can be found here](README.md)
