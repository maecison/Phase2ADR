Decision Title:
Selecting a Navigation Strategy for a Simple Game App

Status:
Accepted

Context: 
For our simple game app, we need to select a navigation strategy. The navigation strategy we pick will impact how our users will navigate through our app. We need to consider different factors that will lead to a more seamless and user-friendly experience. A primary focus for us is to have a straightforward and intuitive design. We want our design to have a familiar feeling with our users, even if it is their first time navigating through it. We would like our users to focus on the gameplay without any distractions.
Option Considered:
- Stack Navigation:
In a stack navigation, screens are arranged similar to a stack of cards. When a user navigates to a new screen, it is pushed onto the stack. When the user wants to go back, the top screen is popped off the stack, and the user returns to the previous screen. This design is used for linear workflows where the user moves froward and backward through a series of steps.
- Drawer Navigation:
Drawer navigation, also known as a side menu, is a design where a menu slides in from the side of the screen. Users can access different sections of features of the app by selecting items from this menu. This strategy is beneficial for apps with many sections or options.
- Bottom Navigation:
Bottom navigation involves placing navigation items at the bottom of the screen. These items represent different sections of the app. Bottom navigation is often used in conjunction with stack or tab navigation and provides easy access to primary app features.

Decision:
After careful consideration and evaluation of the available options, our team has decided to use bottom navigation as the navigation strategy for our simple game app.

Rationale:
Looking at all the different types of navigation options for our app. At first, we considered stack to be our main navigation method. But upon further research we decided bottom navigation would be more beneficial to our user interface. Bottom navigation includes all the perks of stack navigation, while including some key features to create a more intuitive and seamless navigation experience.
- Stack and Bottom Navigation:
Provides a clear and easily accessible menu at the bottom of the screen, allowing users to switch to different screens such as game selection, leaderboard, and settings. While each screen can be handled with stack navigation, to allow linear flow of screens, ensuring users can navigate backwards with ease.

- Intuitive User Experience:
Bottom navigation is widely adopted in mobile apps and provides an intuitive way for users to explore and switch between different sections of the app. It allows users to quickly understand the app’s structure and navigate to their desired content, enhancing user engagement and satisfaction.

- Space Efficiency:
Optimizes screen space by placing the navigation menu at the bottom. By doing this, it leaves more space for the game interface and content, ensuring a clutter-free and immersive gaming experience.

- Consistency Across Platforms:
Using this type of navigation provides consistency in navigation across both Android and iOS platforms. Users familiar with mobile apps on various platforms will find it easy to use and understand.

Consequences:
Choosing bottom navigation will naturally demand additional development resources. We will need to invest time in implementing the code for functional buttons, and there will be a need for more design choices. Given our smaller team size, allocating more of our limited resources is not an ideal situation. However, the advantages significantly outweigh the challenges, justifying our decision.
