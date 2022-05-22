# Grocery List Using AFlat Language

My son DeForestt wrote AFlat, a simple low-level programming language.  [Please read more about AFlat here](https://github.com/DeForestt/aflat). As DeForestt adds new tutorials, I complete them, and occasionally use them as guidance in building my own mini AFlat projects.  Learning AFlat has helped me to understand JavaScript and Python, so not only am I very proud of my son's accomplishment, it is very useful to me!

I will document the progress of my latest AFlat project, a grocery list, here.  So far, I have created a class and verified that it is set up properly by creating two objects and printing out the information of each.

## Table of contents

- [Overview](#overview)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)
- [The Directions](#frontend-mentor---qr-code-component) 

## Overview

My goal is to create a program that can store grocery item objects, including the name of each item, its location in the store, its price, the quantity needed, and whether or not the item has been placed into the shopping cart.  I also want the program to calculate the total price of the grocery bill.



### Screenshots

```
.needs <std>

import * from "io" under io;

class Item {
	adr name;
	adr aisle;
	int price;
	int quantity;
	bool cart;

	Item init(adr name, adr aisle, int price, int quantity, bool cart){
		my.name = name;
		my.aisle = aisle;
		my.price = price;
		my.quantity = quantity;
		my.cart = cart;
	};

	int printInfo(){
		io.print("Grocery List Information:\n");
		io.print("\tName: "); io.print(my.name); io.print("\n");
		io.print("\tAisle: "); io.print(my.aisle); io.print("\n");
		io.print("\tPrice: "); io.printInt(my.price); io.print("\n");
		io.print("\tQuantity: "); io.printInt(my.quantity); io.print("\n");
		io.print("\tCart: "); 
			if my.cart {
				 io.print("✓"); io.print("\n");
	         }else{ 
				 io.print("x"); io.print("\n");
			 };
	};
};

int main(){
	Item i = Item("oatmeal", "bulk", 2, 1, false);
	Item i2 = Item("pears", "produce", 2, 2, true);

	i.printInfo();
	io.print("\n");
	i2.printInfo();

	return 0;
};
```



### Links

- Live Site URL: [name of site](URL)

## My process
I started out creating a grocery item class by using the tutorials student class as a model.  The one main change I had to make was the addition of a boolean field for whether or not the item is in the cart.  If true, a unicode check mark prints. if not, an x prints.


### Built with

- Semantic HTML5 markup
- CSS 3 properties

### What I learned



### Continued development



### Useful resources

- []() - annotation
- []() - annotation
- 
## Author

Faraja Thompson

- [My Personal Website](https://faraja17.github.io/my-website/)
- [My Blog: Teacher to Techie](https://faraja17.github.io/)
- [Faraja Thompson, M.Ed. on LinkedIn](https://www.linkedin.com/in/faraja-thompson-m-ed-70885b8/)

## Acknowledgments

I'd like to acknowledge my son and mentor [DeForestt Thompson](https://github.com/DeForestt).  His steadfast support and encouragement keep me motivated!  Thanks for forcing me to use the command-line, Son <3 <3 <3.
