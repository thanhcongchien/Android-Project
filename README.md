# ChatApp


I have deleted google-services.json. Add yours
Change Authorization:key with your key from firebase project


Implementation Guide
1 - Project
1 - Open the Project in your android studio;
2 - IMPORTANT Change the Package Name. (https://stackoverflow.com/questions/16804093/android-studio-rename-package)


2 - Firebase Panel
- Create Firebase Project (https://console.firebase.google.com/);
- Import the file google-service.json into your project
- Connect to firebase console authentication and database from your IDE 
- in firebase Storage Rules, change value of "allow read, write:" from "if request.auth != null" to "if true;" 

![1](https://user-images.githubusercontent.com/55091674/93608808-43526b00-f9f5-11ea-8982-52d67b6f1d35.jpg)
![2](https://user-images.githubusercontent.com/55091674/93608620-04bcb080-f9f5-11ea-80d6-e483e4e3df5d.jpg)
![5](https://user-images.githubusercontent.com/55091674/93608663-11d99f80-f9f5-11ea-91b9-198386fcf591.jpg)
