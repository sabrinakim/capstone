# food360

Original App Design Project - README Template
===

## food ordering app for college students

## Table of Contents
1. [Overview]
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
College students can easily find others near them on campus to create a group UberEats order with. This will help reduce the expensive delivery fees per person. Use https://developer.uber.com/docs/eats/introduction api?

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Food/Social
- **Mobile:** Easy access
- **Story:** Allows college students can easily find others near them on campus to create a group ubereats order with. This will help reduce the expensive delivery fees per person.
- **Market:** College students living on campus
- **Habit:** Users can check app everytime they want to order food with a food delivery service, like UberEats.
- **Scope:** UberEats

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can login, signup, and logout of account
* Users will be brought to a series of pages that require them to specify these personalized parameters:
    * 1) "How many people do you want to split with?"
    * 2) "Which meeting locations do you prefer?"
    * (these parameters will be used to find users compatible to them)
* User can scroll through available restaurants to order from in a "restaurant feed"
    * these restaurant cards must include a cover photo, name of restaurant, and the number of "likes" from users they are compatable with
* User can double tap on a restaurant card to be brought to a modal overlay that makes them enter their order & set their "timer"
    * "timer" specifies how long this user is willing to wait until a group order is placed.
* User can click on the number of "likes" to view who liked the restaurant
    * this "likes" page will show each user and their order
        * (Bob: 20 piece chicken nuggets)
* Users can select users from the "likes" page to create a group order
    * this user will then be redirected to the UberEats app to create the order.
* Users can navigate to an "orders" tab
    * Users can view their order and the name of the person who ordered


**Optional Nice-to-have Stories**
* Restaurants with the most activity ("likes") will be bubbled up to the top of the feed
* Users can "pin" restaurants, so the corresponding restaurant cards show first in the feed.
* Users can also add users to their "close friends" list
* Users can navigate to a "profile" tab

### 2. Screen Archetypes

* Login/signup screen
   * user can login/signup
* Restaurant Feed (like UberEats)
   * User can scroll through available restaurants to order from
* Defining preferences pages
    * "How many people do you want to split with?" page
    * "Which meeting locations do you prefer?" page
* Modal overlay that requires ursers to enter their order and set a "timer"
* Order screen

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Restaurant Feed
* Orders

**Flow Navigation** (Screen to Screen)

* Restaurant card -> details page that uncover the menu


## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
