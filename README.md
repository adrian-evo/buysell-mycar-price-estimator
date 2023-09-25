<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# buysell-mycar-price-estimator
A very simple and highly particular price estimator for selling and then buying your next used car.

## Summary

The purpose of this project is to provide a custom AI tool that can be used to predict the sale price of own car and the right buying price of one particular car we are interested to purchase, based on a set of custom defined characteristics and a list of similar cars data that are currently under sale.

The idea of the project comes from "Building AI course project" by Helsinki University.

## Background

Many of us are sometimes struggling with selling own used car and then buying another used car, both with the right price, while we would like to avoid the easy path of giving the car to a dealer and buying the next one from the same dealer, which means big losses.

With the help of AI methods, particularly linear regression and neural networks, we can collect the actual data of similar used cars under sale, with a set of defined parameters that are important for us, and then predict the price for selling our car. The same goes for collecting the actual data of similar cars with the one we would like to purchase, and predict if a particular car we are interested in have the right price and thus getting the knowledge to negotiate.

## How is it used?

The solution will be provided in a form of an Excel in Windows or Numbers in MacOS, with Python code in the background for estimating the parameters and then the prices with the defined AI methods.

The user will collect a list of cars data similar to own car, or similar to the car to be purchased.

Then the user will define a list of characteristics that are relevant, for example:

- The manufacture year of the car
- Number of kilometres or miles
- Fuel type, e.g. Petrol, Diesel, Hybrid, Electric
- Basic, premium or luxury equipment
- Tyres quality
- Car had traffic incidents or not
- Car has only summary or very detailed description
- Other relevant characteristics important for the user

## Data sources and AI methods

As we already know, many online advertising sites that are used for selling and buying used cars are already estimating with AI methods if the price of a listed car is having the right medium price, or is under or over priced. However, relaying on the given site estimate might not be accurate for the particular user case and own interest. That's why collecting own data from multiple such sites, defining own characteristics we are interested in will make it possible to predict more accurately the price of the car we want to sell or purchase.

## Challenges

Of course the users should understand that this is just a not binding tool, that should help in the selling or the purchase decision. When we have a somehow special car that only few are available under sale, or if we are interested for a particular rare car, this AI method obviously will not work since the available data is not enough. 

## What next?

Having a public site where it would be easier to input data, and get as output the predicted right price, and also being able to play with different characteristics and see how these will affect the final price.
