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
2  Copy the folders from the 'nativemobile' folder to 'Native Mobile Resources / Native Builder Profiles / [required environment]
   
3. Build your app 
4. Delete the contents of 'nativemobile' folder 
5. Commit the configurations included in Native Builder Profiles folder

## Usage after setup

To use this folder afterwards: 
1. Copy the contents of Native Mobile Resources / Native Builder Profiles / [required environment] folder to the 'nativemobile' folder
2. Open the Mendix Native UI Builder
3. Check if the Apple and Android certificates are included into the builder, update if necessary. 
4. Build your app 
5. Copy the contents of the 'nativemobile' folder to 'Native Mobile Resources / Native Builder Profiles / [required environment]'
6. Delete contents of 'nativemobile'
7. Commit

This process ensures that all team members work with the same configuration. 
