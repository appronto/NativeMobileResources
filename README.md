# Native Mobile Resources
Default folder structure that can be used to organize all necessary files and assets for a **Mendix Native Mobile** project.

## First setup
1. Copy the folder 'Native Mobile Resources' to the root of your Mendix Project folder.
2. Add the contents to the **All Environments** folder. First complete the Intake form.
3. Add the contents to the **Assets** folder
4. Add the contents to the **Enironments** folder
5. Add the contents to the **Native Builder profiles** folder

To setup the **Native Builder Profiles** folder: 
1. Complete the Mendix Native UI Builder configurations. 
2. Build your app.
3. Delete builds folder from 'nativemobile' folder.
4. Copy the folders from the 'nativemobile' folder to 'Native Mobile Resources / Native Builder Profiles / [required environment]
5. Delete the contents of 'nativemobile' folder 
6. Commit the configurations included in Native Builder Profiles folder

## Usage after setup

To use this folder afterwards: 
1. Copy the contents of Native Mobile Resources / Native Builder Profiles / [required environment] folder to the 'nativemobile' folder
2. Open the Mendix Native UI Builder
3. Check if the Apple and Android certificates are included into the builder, update if necessary.
4. Check if Appcenter and Github API keys are included into the builder, update if necessary.
5. Check Github API Organization. 
6. Check if Github and Appcenter folders are correct. 
7. Build your app.
8. Delete builds folder from 'nativemobile' folder.
9. Copy the contents of the 'nativemobile' folder to 'Native Mobile Resources / Native Builder Profiles / [required environment]'
10. Delete contents of 'nativemobile'
11. Commit

This process ensures that all team members work with the same configuration. 
