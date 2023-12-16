# To-Do List

## Languages Used
 - React + Vite

## How it works
 - Header Component
    - Containes a Input field for Name and Description
    - By clicking the Add To-do Button the details entered
    - in the input field will be created as a To-Do card
    - with 'Not Completed' as a default Status
    - button and the input field will be updated for edit the card
    - when the edit button in card is pressed
- Filter Component
    - it has a Filter option with Three option
    - All, Not Completed, Completed
    - To-do card with the selected option will be shown in the card-container
- Card Container
    - Have a card for each To-Do task
    - Contains name, description, status and buttons
    - Status will be updated to the original data upon selection
    - Edit button will be get a original data from the card
    - And update it to the Input field in the header and also changed the 
    - 'Add To-do' button in the header to 'Save'
    - The Delete button will delete the card

## Run Command 
    `npm run dev`

    
-[Live Site](https://to-do-list-8161.netlify.app/)
