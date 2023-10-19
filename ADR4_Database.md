Decision Title:
Selecting Database Storage for a Simple Game App

Status:
Accepted

Context: 
Our team needs to decide on database storage to provide fast access to game state and user preferences while ensuring user data is secure on the device. We also need to decide whether to include data encryption or not.
Option Considered:
- Local Database (Encrypted)
Local databases are stored directly on the user’s device. Using encryption algorithms to secure data, making it unreadable without the decryption key. 

- Local Database (Unencrypted)
Similar to the option above, just removing the encryption. The local database will just store data in plain text on the user’s device.

- Remote
Remote database store data on servers hosted in the cloud. Apps connect to these databases via APIs, allowing data to be accessed and manipulated remotely.

- No Database
Apps with minimal data requirements opt not to use any formal database system.

Decision:
After evaluating the requirements and considering our app’s simplicity, offline functionality, and user privacy concerns, our team has decided to use local database with encryption as the storage solution for our simple game app.

Rationale:
We opted for a local database with encryption to prioritize the security of our users' data. This choice not only ensures data protection but also offers swift read and write operations.
- Offline Availability:
Allows our users to continue playing our simple games even without internet connection, providing a seamless gaming experience.

- Data Security
By choosing an encrypted local database, sensitive user data can be securely stored on the device. Encryption adds an extra layer of security, ensuring that user profiles and game progress are protected from unauthorized access.

- Simplicity and Performance:
For a simple game app like ours, a local database with encryption offers a balance between simplicity and performance. It eliminates the complexities associated with setting up and managing a remote database while still providing data security.

Consequences:
Picking a local database does have some drawbacks. If data on the device were to be corrupted or lost, any game progression and user information could be lost forever. Also, synchronizing encrypted local databases across multiple devices or users can be complex, especially in real-time scenarios. Lastly, setting up encryption processes adds complexity during the initial development phase, potentially requiring additional time and resources. Despite these cons, we believe that this option is the best suited for our application.
