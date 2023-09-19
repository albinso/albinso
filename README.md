

<!--
**albinso/albinso** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# Projects

## Routine Manager [Unpublished]

A productivity tool that manages recurring tasks. Routine definitions are managed by the user who can specify timing and location conditions for a task to trigger. Once all criteria are fulfilled the app notifies the user that the task needs to be performed. A record is kept of all tasks, completed and cancelled, and the time spent on them. Future work includes presenting this data to help the user understand their habits and improve their productivity.

The app is built with React Native and Expo. The backend is built with Node.js and hosted as Azure functions. The database is a Cosmos DB instance. Authentication is handled via Google Signin but support for other providers is planned. At this time the app only supports Android.

More comprehensive documentation is available in the repositories:
- [App](https://github.com/albinso/routine-app)
- [Backend Services](https://github.com/albinso/routine-api)


### Example with a single routine due for completion:

<img src="Screenshot_20230915_230159_Routine Manager.jpg" alt="drawing" width="200"/>

## GeoLog [WIP]

A location logging app that allows the user to record their location and activity. The app is intended to give users ownership of their own location information. The core concept is that all location data is encrypted on the client with a user provided key before being sent to the server to ensure that no one but the user can gain access. Once retrieved and decrypted the user can export all or a subset of the data to other services.

This is currently in early stages of development and central features such as encryption and export are not yet implemented. The app is only tested for Android.

The app is built with React Native and Expo. The backend is built with Node.js and hosted as Azure functions. The database is a Cosmos DB instance. 

- [App](https://github.com/albinso/geolog-app)
- [Backend Services](https://github.com/albinso/geolog-api)




