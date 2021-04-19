Original App Design Project - README Template
===

# CarShare

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Carshare is an app the allows users to rent people's personal cars for their trip.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Travel
- **Mobile:** The app will start out just for mobile phones then it will eventually be able to be used on the computer. 
- **Story:** The app will take the pickup location and dates the car will be used and give the user the cars that will be available to rent.
- **Market:** Anyone that wants to rent a car but not through a big rental company.
- **Habit:** The app will be used as much as the user wanted to travel or needs to rent a car. 
- **Scope:** First the app will just be used in the United States then eventually the app will be used worldwilde.

## Product Spec


# README Template

Your [design product spec](https://hackmd.io/s/H1wGpVUh7) (described in that link) will look like the following in your README:

## 1. User Stories (Required and Optional)

**Required Must-have Stories**

 * User can register for an account [x]
 * User can login [x]
 * User can choose location to get car [x]
 * User can choose dates to pick cars [x]
 * User can see all the cars [x]
 * User can leave review about the car[x]
 

**Optional Nice-to-have Stories**

 * putting their own car on to the app
 * selecting a specific car type to rent 
 * maps shows all cars near the user to rent 
 

## 2. Screen Archetypes

 * Login
     *  User can login 
 * Filter
     *  User can choose location to get car 
     * User can choose dates to pick cars 
 * Stream
     * User can see all the cars
 * Creation 
     * User can leave review about the car
 * Register
     * User can register for an account 
 
     

## 3. Navigation

**Tab Navigation** (Tab to Screen)

 * Stream
 * Filter 
 * Profile 

**Flow Navigation** (Screen to Screen)

 * Login
     * Stream 
 * Register
     * Stream
 * Filter 
     * Stream
 * Stream
     * creation
 * Creation 
     * stream 
 

## Wireframes
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

### [BONUS] Digital ![](https://i.imgur.com/Au7cAxA.png)


### [BONUS] Interactive Prototype
![](https://i.imgur.com/3RKYtrL.gif)


## Schema 
Property	  | Type  |        Description        |
| :--------- |:-----:| -------------------------:|
| CarID      | String| Unique ID for Cars posted |
| Carimage   | File  |   		Image of vehicle      |
| review     | Review| comment of vehicle posted |
	

### Networking
Networking
List of network requests by screen
•	Sign Up Screen
 o	(Update/PUT) User Sign Up
func myMethod() {
  var user = PFUser()
  user.username = "myUsername"
  user.password = "myPassword"
  user.email = "email@example.com"

  user.signUpInBackground {
    (succeeded: Bool, error: Error?) -> Void in
    if let error = error {
      let errorString = error.localizedDescription
      // Show the errorString somewhere and let the user try again.
    } else {
      // Go to Home Screen
    }
  }
}

•	Login Screen
 o	(Update/PUT) User log in

PFUser.logInWithUsername(inBackground:"userName", password:"passWord") {
  (user: PFUser?, error: Error?) -> Void in
  if user != nil {
    // Go to Home Screen
  } else {
    // The login failed. Check error to see why.
  }
}

•	Home Feed Screen
 o	(Read/Get) View posts of vehicles
 o	(Read/GET) View reviews of vehicle
 o	(Create/POST) User can create reviews of vehicle
•	Filter Screen
 o	(Read/GET) Get pickup/drop off location and Start/End date from USER
•	Profile Screen
 o	(Read/GET) Query logged in user object
 o	(Update/PUT) Update user profile image



## Unit 10 Update![](https://i.imgur.com/JaEqDsV.gif)

## Unit 11 Update 
![](https://i.imgur.com/IrR2lr0.gif)

## Unit 12 Update 
![](https://i.imgur.com/wCMxyjQ.gif)
## Unit 13 Update 
![](https://i.imgur.com/C2jN4kk.gif)


