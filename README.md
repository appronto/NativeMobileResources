# Native Mobile Resources
Default folder structure that can be used to organize all necessary files and assets for a **Mendix Native Mobile** project.

## Usage
1. Copy the folder 'Native Mobile Resources' to the root of your Mendix Project folder.


### Native Builder Profiles

When you first build your app, the 'nativemobile' folder in your project directory is set up with the following structure. 

- assets
- firebase
- fonts
- .config file

The .config file contains all the necessary configurations. To use the assets, firebase configuration and fonts, the .config file links to the folders in the 'nativemobile' folder. 

To setup this folder: 
1. Complete the Mendix Native UI Builder configurations. 
2  Copy the folders from the 'nativemobile' folder to 'Native Mobile Resources / Native Builder Profiles / [required environment]
3. Build your app 
4. Delete the contents of 'nativemobile' folder 
5. Commit the configurations included in Native Builder Profiles folder 

To use this folder afterwards: 
1. Copy the contents of Native Mobile Resources / Native Builder Profiles / [required environment] folder to the 'nativemobile' folder
2. Open the Mendix Native UI Builder
3. Check if the Apple and Android certificates are included into the builder, update if necessary. 
4. Build your app 
5. Copy the contents of the 'nativemobile' folder to 'Native Mobile Resources / Native Builder Profiles / [required environment]'
6. Delete contents of 'nativemobile'
7. Commit

This process ensures that all team members work with the same configuration. 
