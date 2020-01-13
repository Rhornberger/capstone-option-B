## Stitch-a-Pic

## Project Overview

- Convert uploaded image into Cross Stitch pattern.
- Allow user to choose preferred thread company and receive a custom list of color correct threads for their project.

- Convert any image to easy to read pattern.

- What libraries or frameworks will you use?
    -I need to find an image manipulation Api that will work for what I want to do.
    -I think I will be mostly doing this useing the Ajax framework.

## Features

Walk through the application from the user's perspective. Think about features in terms of **user stories**.

### User stories

User stories follow this template:
"As a fiber artist, I want the ability to make any image into a cross stitch pattern."
**Tasks:**

- Upload image and store in db
- Interpret image by color of pixel, and assign symbol for color
- Return grid with symbol overlay
- Make new file available to user
- Return list of symbol and key for colors/numbers


#### Questions to ask yourself about functionalities

What will the user see on each page? What can they input and click and see? How will their actions correspond to events on the back-end?
-User will see a window to upload image that they want to turn into a pattern. The image can be saved to DB.
-User will see a page that asks them to sign in or create an account. The account will be saved in a DB.
-After user opts to create a pattern from the image the pattern will display and give the option to save to their computer files, as well as print out. The pattern will save into their account DB. 
-User will have access to their own account page and can navigate from there.

## Data Model

'Image' 
'User'
'Account'
'Symbols'
'Threads'


## Schedule

    ** tentative schedule**

        -Days 1-2: Set up enviroment with basic database, find image manipulation API, send Email to thread companies to accuire access to their color Databse. Sketch out the basic overall design of the page.
        -Days 2-5: Put in functionality to upload a picture of user choice, and start on the functionality of breaking it apart by pixel.
        -Days 6-9: Put in functionality to assign a sybol to the individual color in the pixel, and render the image broken up by pixels with the symbol overlaid on the pixeled color to the page, have the symbols render as a key with the color as the value of the symbol and print a list on screen  as a color map, allow the "pattern" to be sent to print. Create basic css for the page display
        -Days 10-13: Add in account creation and use functionality, to include the ability to save images and created patterns to personal accounts.
        -Days 14-15: Fine tune the design and presentation of the website itself. 

        -What I want to accomplish after the capstone presentation: 
            -Add in addition stitch functionality to include backstitches and pearls stitches.
            -Turn this into a funtional app and add it to the apple app store. 