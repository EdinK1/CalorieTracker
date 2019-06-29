# [CalorieTracker](https://calorietracker.netlify.com//)

### This app allows you to manage your count your meals and manage your calories

# Technologies used
1. HTML5
2. Materilaze
3. Javascript
4. Module Pattern
5. Local Storage

<p align="center">
<img src="https://user-images.githubusercontent.com/38442554/60380494-788f2980-99fb-11e9-83ba-4e748a62a9f7.PNG" width="730px" height="400px">
</p>

# How it works

The app is pretty simple to use. You just add your meal and its calories and that gets added to the total calories.
You have the option to update or delete a meal. You can also delete the entire collection as well.

<p align="center">
<img src="https://user-images.githubusercontent.com/38442554/60380505-a70d0480-99fb-11e9-90d8-4745e516195e.PNG" width="730px" height="400px">
</p>

# How it works (Under the hood)

Basically, I have few different controllers. I have a Storage controller which persists our data so that it stays after we reload the page or close the browser. An Item controller which deals with data and state. I also have a UI controller which handles everything the user sees. Showing, hiding, getting input values and such and last but not least is the App controller which is the initializer. 

# My notes about the project
This project was pretty fun to build. It requires more code since I'm not using any libraries or anything. I really like the module pattern design. It is a very powerful and maintainable way of structuring code. I definitely see myself using this pattern more often from now on. Overall, it was a good project and I learned quite a lot.
  
