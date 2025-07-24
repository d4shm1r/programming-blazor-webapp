## Basic Project Structure

Whenever you create a new project you will see this template structure in **VS Code**:

![Project Structure](https://github.com/d4shm1r/programming-blazor-webapp/blob/198a1289fc21f4b14ed407d01af59bd45115a437/images/ProjectExpansion.png)


## What's Important


- Program.cs – It's where you bootstrap the app. Think of it like your app's entry point.

- App.razor – Handles routing using <Router>. It decides what component gets shown for which URL.

- Pages/ – The meat of your app: each .razor file is a mini web page/component.

- Layout/ – If you’re reusing UI elements (like navbars or headers), they go here.

- wwwroot/ – It’s your “public” folder. Drop in images, JavaScript, CSS, etc.
