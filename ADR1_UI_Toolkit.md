Decision Title:
Selecting a UI Toolkit for a Simple Game App

Status:
Accepted

Context:
Our team was tasked with selecting an appropriate UI Toolkit for our simple game app, which includes tic-tac-toe and a memory game. The app is targeted for Android devices using React Native as the development framework. The choice of a UI Toolkit is crucial as it impacts the user interface and experience for mobile applications. Our primary focus is creating an intuitive and visually appealing user interface for our minigames.
Option Considered:

- React Native Elements: 
React Native Elements is a UI Toolkit that has built in extensive pre-designed components such as buttons, cards, input fields, and more. Other advantages are the ease of customization, active community support, and integration with React Native. The disadvantages are limited customization for more complex designs and the creation of larger file sizes as it depends on the components you pick and how extensively it is customized.

- Native Base:
Native base is a UI Toolkit that includes a wide range of UI components, making it suitable for diverse app interfaces and customizable to match specific design requirements. Native base is complex with the variety of components it provides and can have a steep learning curve for developers who are unfamiliar with toolkits. 

Decision:
After careful evaluation of the available options, our team has decided to use React Native Elements as the UI Toolkit for our simple game app.
Rationale:
Our team has chosen React Native Elements for our UI Toolkit. After taking into consideration our smaller team size who are relatively new to toolkits, React Native was the clear winner in our architecture decision. 
- Extensive Pre-Designed Components:
React Native Elements provides a wide variety of pre-designed components such as buttons, cards, input fields, and more. These components save development time as they can be easily integrated and customized for our app’s specific needs.
- Active Community Support:

Since our team is made up of newer developers, it is important that the toolkit we pick has a large and active community. Community support is valuable for troubleshooting issues, finding solutions to problems, and accessing additional resources, tutorials, and third-party libraries.

- Integration with React Native:
Being specifically designed for React Native, React Native Elements integrates seamlessly with our React Native project. Making it a natural choice for our developers to work within the React Native ecosystem.

- Documentation:
React Native Elements comes with comprehensive documentation. Clear and detailed documentation is crucial for developers to understand how to use components effectively. It provides guidelines and examples, making the implementation process easier and faster.

Consequences:
By choosing React Native Elements as the UI Toolkit, we might reach a point where the limited customization complexity of this toolkit could hinder our chance to create a more unique and intricate design. Basic customization with React Native Elements is more straightforward, but more advanced customization will have a deeper learning curve. This will inherently take more of our limited time and resources to learn if we choose to venture off into more advanced customization. Lastly, pre-designed components are great for newer developers but could affect our application’s file size, due to the additional code and styles included in the components. For the most part it is generally minor but can add up, especially for apps with strict size constraints.
