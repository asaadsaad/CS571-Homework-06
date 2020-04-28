# CS571-Homework-06
## Updates to Tabata Timer App
### Add Logo
Add your logo image to be displayed in the top middle section of your home screen. (Bare in mind platform compatibility)
  
### Add Inputs
Previously, we created a Tabata application that has 10 sets/cycles by default. Also a preset workout/rest time of 20/10 seconds.  
Update your Tabata application to accept the following inputs:
* Number of sets/cycles
* Number of seconds for workout
* Number of seconds for rest
  
All three inputs should be displayed in a single row, above your **Start Workout** button.
  
### Workouts List
Save all of the user's completed workouts in the form of:
```javascript
[ {year: '2020' , month: '04', day: '28'} ]
```
Use `FlatList` component to display all of the workouts When users click a button: **Previous Workouts** from your home screen.
