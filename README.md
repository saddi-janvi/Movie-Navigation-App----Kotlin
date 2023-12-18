# Movie-Navigation-App--Kotlin


This Android app enhances user navigation and interaction through a navigation drawer and two activities with RecyclerView fragments. The app focuses on a visually appealing UI and implements various navigation and interaction features.

## Table of Contents
1. [Task 1 - Navigation Drawer](#task-1---navigation-drawer)
2. [Task 2](#task-2)
3. [Task 3](#task-3)

### Overview
The quality of the UI will be evaluated based on its appearance and user experience.

## Task 1 - Navigation Drawer

### Implementation
The navigation drawer serves as the top-level navigation with the following components:
- A visually appealing banner (header)
- At least 3 items, each containing an icon and a title
  - "About Me" fragment
  - Activity for Task 2
  - Activity for Task 3

## Task 2

### Activity Implementation
This activity loads a RecyclerView fragment, reusing components from Assignment 5:
1. **Toolbar Usage**
   - Utilizes a Toolbar for the activity's action bar
   - Displays an ImageView and TextView on the Toolbar to show a picture and title
2. **SearchView**
   - RecyclerView Fragment's action bar contains a SearchView
   - Enables scrolling to the first movie item containing the search string
   - Displays a message if no matching item is found
3. **Contextual Action Bar**
   - Appears on long-click with choices to duplicate or delete the selected item
4. **ImageView Popup Menu**
   - Each item has an ImageView; clicking opens a popup menu with duplication and deletion options
5. **Item Click**
   - Clicking a list item loads the detail view fragment of the selected movie in the same activity
   - Detail Fragment includes a Share action provider on the action bar for sharing movie information
   - Tap on specific text in the description TextView triggers a popup Contextual Action Bar for copy and paste.

## Task 3

### Activity Implementation
This activity replicates Task 2 with additional features:
1. **Standalone Toolbar**
   - Adds a standalone Toolbar at the bottom of the activity
   - Contains sorting options for title and rating
2. **Sorting Buttons**
   - Enables sorting of movie data by title and rating
3. **Toolbar Hide/Unhide**
   - Includes buttons to hide and unhide the standalone Toolbar

### Prerequisites
List any prerequisites or dependencies that users need to have installed before using your app.

### Installation
Offer step-by-step instructions on how to install and set up your Android app.

### Usage
Explain how users can navigate and interact with the app, highlighting specific features implemented in Task 2 and Task 3.
