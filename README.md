A Recipe Book - Angular
1. Have an Authentication Functionality so as to Login, Logout and Signup.
2. On Logging In we can add Recipe and the ingredients required for the Recipe along with Recipe Details.
3. We can save and fetch Recipe data from the Firebase DB.
4. We can edit Recipe and Delete Recipe.
5. We can add the ingredients of a recipe to a shopping List directly.


How to get the API Key:
1. Go to https://firebase.google.com/
2. If you have an account login otherwise you can create a new account.
3. Click on "Go to Console" button.
4. Click on "Add Project" and give a name to it.
5. Create you project.. It may take some time.
6. On clicking Project Settings you can get the Web API key.
7. Click on the Authentication -> Sign-in method and enable the Email/Password.
7. Add it like firebaseAPIKey: "Your api key" in evironment.prod.ts and environment.ts files.

Get the DB URL:
1. Go to https://firebase.google.com/
2. If you have an account login otherwise you can create a new account.
3. Click on "Go to Console" button.
4. Select your project that had been created.
5. Click on Database.
6. Create a real time Database by keeping it in test mode for now.
7. Get the database URL in format https://ProjectName.firebaseio.com/recipes.json and paste it in app -> shared -> data-storage-service.ts file in the storeRecipes and fetchRecipes methods in the 21 and 32 lines.
