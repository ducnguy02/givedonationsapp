# Give Donations App solution template
The app enables you to get in touch with local initiatives which support people in need.  See what the current need is and how you can help.  You can see a list of all nearby initiatives and also what they request in terms of material donations or services requests. Interact with community by liking the item you have donated or sharing a post with a photo inside the comment section.
This app is built on Microsoft Power Apps.

# Prerequisites to use the app:
- Power Apps standalone license or similar (Power Apps per app/per user or Dynamics 365 plan licnese)
- Environment with Dataverse set up
- Activate geospatial feature in your environment (How to: https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/geospatial-overview#:~:text=Enable%20the%20geospatial%20features%20for%20the%20environment,-Before%20you%20can&text=Open%20the%20Power%20Platform%20admin,the%20toggle%20switch%20to%20On.)

# What's inside the solution
- Power Apps Canvas App
- Power Apps Model-driven app, with five tables
- Two security roles (Give Donations Admin, Give Donations Basic User)

# How to install
1. Download the GiveDonationsApp_1_0_0_2.zip file 
2. Go to a make.powerapps.com and select the Dataverse environment to import the solution (How to: https://docs.microsoft.com/en-us/powerapps/maker/data-platform/import-update-export-solutions)
3. Go to the Give Donations Canvas App in the Apps section > Share > Select the users and inherit the Admin or Basic User security role (How to: https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/share-app)

# Remarks
- You might need to replace the dummy logo inside the Canvas App with your own logo by importing an image file, name it "logo01" (How to: https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/add-images-pictures-audio-video)
- In order to start the Model-driven app it needs to be published after the import (How to: https://docs.microsoft.com/en-us/powerapps/maker/model-driven-apps/validate-app)
- The Give Donations Admin security role allows users to delete data records from the Model-driven app and the user can read all data from the five relevant tables
- The Give Donations Basic User security role allows users to delete their owned records only from the Model-driven app and the user can read all data from the five relevant tables
