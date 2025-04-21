# CS-360

App requirements & goals
The Goal Weight Tracker mobile application was developed in order to demonstrate a complete mobile app development cycle, starting from initial UI design to fully functional implementation and testing. The app helps users track their daily weight entries and progress toward a personal goal weight, addressing the common need for simplistic and goal-oriented health tracking.

Necessary screens & UI design
The app’s UI was designed with accessibility, and user-centered functionality both in mind. Some of the necessary screens implemented were a login/registration screen, a data display screen showing logged weights in a RecyclerView grid, a log entry screen for new weight entries, and an SMS permission screen that allows users to opt in for progress notifications. The labeled "Log Weight" button and goal weight interface on the data display screen make it easy for users to interact with the app’s core functions. The notifications giving user’s encouragement when users reach their goals was a feature designed to boost user engagement over time.

Coding approach
To build the app I used Android Studio and Java, employing SQLite for persistent data storage. I approached coding modularly by first developing each UI screen and then connecting them with logic. This was followed by database integration and finally implementing advanced features like SMS permissions and notifications. I used best practices like separating responsibilities across classes, writing inline comments to keep my code organized and readable, and naming various elements clearly. These strategies help maintain readability and can be reused for any project going forward.

Testing and debugging
Throughout the development process I used the Android Emulator testing and debugging. Each screen, button, and database function was tested iteratively, including handling edge cases like empty input, denied permissions, and login validation. This process revealed a few challenges, especially with XML layout errors and RecyclerView issues, but ultimately ensured a stable and functional application.

Challenges and innovations
One of the major challenges was coordinating SQLite data flow across multiple screens while maintaining real-time updates to the app. To solve this I implemented live data refresh through onResume() and dynamically updating RecyclerViews. Another unique feature was the implementation of SMS notifications triggered only when a user logs a weight that meets their goal. This required thoughtful condition checks and permission handling to implement properly.

Demonstrated skills and strengths
The component that best highlights my development experience is the data display screen with full CRUD operations and the integrated RecyclerView. This section demonstrates my knowledge of backend and frontend integration and dynamic updates which are all essential skills for professional development.
