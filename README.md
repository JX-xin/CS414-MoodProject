# CS414-MoodProject
Authors: Lirim Mehmeti and Jiaxin Jiang
# Description of the App

##### The app is Mood Diary, which is used to record the mood of the user, monitor user's energy bar, write diaries and get their emotion analysis, and user can also read and search the positive quotes to encourage themselves.

1. Use navigation drawer to navigate to different activities
2. Mood list main activity (a mood listview to show the mood, a float button to add the mood, a progress bar to show the positive and negative emotions proportion, long click to delete and a card dialog of corresponding quote will pop out when clicked, a music logo rotation animation)
3. Add mood activity (user can choose a time and a mood and save the mood)
4. Search quotes activity (search any quotes by inputting a search term)
5. A notification to notify that the app is running
6. A media player playing music in the background
7. Diary activity(user can write the title and content of the diary, post it, update it, or delete it, and user can get the text emotion analysis by clicking the analysis button, and the result can be shown in a dialog with numbers and a pie chart)
8. Recyclerview (in the diary activity to show the view of diaries)
9. DiaryViewModel(implement the method to operate the diaries)
10. Room Database(used to store, read, update, delete the title and content of the diaries)

# References

1. navigation: activities (java version) 

   [How to Implement Navigation Drawer With Activity in Android Studio | NavDrawer | Android Coding](https://www.youtube.com/watch?v=iesMhKUtYT8&list=PLkbnctMtUcaT1he4QO6Oqfth3cRoEOQUJ&index=4&t=1427s) 

2. gradient background 
   [Make a Weather App for Android | Android Studio | Kotlin](https://www.youtube.com/watch?v=gj0g1a75Lmo&list=PLkbnctMtUcaT1he4QO6Oqfth3cRoEOQUJ&index=2&t=172s) 

3. Pie chart: [*Implement Pie Chart in Android Studio Using Kotlin | #OttomanCoder*](https://www.youtube.com/watch?v=28IKmy-HCSk)



# Instructions to run App

1. It’s suggested to use Api 30 of the virtual device 

2. Tested device: Pixel 5 API 30, Nexus 5X API 30 

# Some Screenshots of Main Functions
<img src="https://user-images.githubusercontent.com/66004742/216561998-ba06db94-628a-4c83-aa56-82d90c2d77cb.png" alt="Index" width="300" height="400"> <img src="https://user-images.githubusercontent.com/66004742/216564935-03f042bf-d340-48e3-82c7-76749dc1eaa7.png" alt="Write a Diary" width="300" height="400"> <img src="https://user-images.githubusercontent.com/66004742/216566420-dbd470aa-98ce-48af-959b-625a41eb6312.png" alt="Text Emotional Analysis" width="300" height="400">



