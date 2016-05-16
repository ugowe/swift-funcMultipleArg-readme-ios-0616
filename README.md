# Functions with Multiple Arguments

![Neil](https://pbs.twimg.com/profile_images/74188698/NeilTysonOriginsA-Crop_400x400.jpg)  
> For me, I am driven by two main philosophies: know more today about the world than I knew yesterday and lessen the suffering of others. You'd be surprised how far that gets you.


## Learning Objectives - The student should be able to..

* Explain that a function is a self-contained chunk of code that performs a specific task. A function should do one thing and one thing well.
* Explain that a function has a name that identifies what it does, and that name is used to "call" the function to perform its task when needed.
* Create functions that contain multiple arguments


## What the student can do at this point 

* Create variables and constants
* Knows how to use the print function (although they might not know that it's referred to as a function at this point).
* Can create variables of type String and Int (no other types).
* They would have learned what functions are and will be just coming off having completed a functions lab in Playground.
* They would have completed a lab in a playground file which had them work with the following - String, Int, variables, constants, print, string interpolation, type inference, type annotations.


## Outline / Notes

* Explain again how to create a function and break it down.
* Explain again how we name the function and put in the ( ) the various arguments separated by comma's. 
* Explain how the first argument in calling on a function (it's external name by default is omitted) and another further aguments, their external name (which is also used internally displays).
* Final outcome of what the student should understand:

```swift
func planetDescription(planet: String, numberOfMoons: Int) {
    print ("There are \(numberOfMoons) moons orbiting \(planet).")
}

let planet = "Jupiter"
let moons = 67

planetDescription(planet, numberOfMoons: 67)
// prints "There are 67 moons orbiting Jupiter."
```

<a href='https://learn.co/lessons/FunctionsMultipleArg' data-visibility='hidden'>View this lesson on Learn.co</a>
