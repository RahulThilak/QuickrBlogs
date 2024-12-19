QuickrBlogs
A React application simulating a minimalist blog with features for adding, searching, and archiving posts. The app uses faker.js to generate random posts, and Context API for state management across components.

Features
Add Posts: Users can add new blog posts with a title and body.
Search Functionality: Search through posts using a simple input filter.
Dark Mode Toggle: Toggle between light and dark mode themes.
Archive: Displays a list of generated posts that can be added to the main feed as new posts.
Clear All Posts: Option to clear all posts from the main feed.
Project Structure
This project is built using functional components and React hooks for managing state and context.

Components
App: Main component that wraps the entire blog structure.
Header: Contains the app’s title, search bar, and clear posts button.
Main: Holds the form to add posts and displays current posts.
FormAddPost: A form for adding new posts with title and body.
List: Renders the list of posts.
Archive: An archive of pre-generated posts that can be added to the main list.
Footer: Displays a footer message.
Dark Mode Toggle: A button to switch between light and dark themes.
Key Functions
Dark Mode Toggle: setIsFakeDark state to toggle the fake-dark-mode class on the document root.
createRandomPost: Generates random titles and bodies using faker.js.
onAddPost: Adds a new post to the main list.
onClearPosts: Clears all posts from the main feed.
onSearch: Filters posts based on the search query.
Technologies Used
React: Core framework for building the UI.
React Context API: For managing state across components.
faker.js: Generates random post titles and content.
CSS: Basic styling for layout and dark mode.
Setup
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/yourusername/quickrblogs.git
Navigate to the project folder:

bash
Copy code
cd atomic-blog
Install dependencies:

bash
Copy code
npm install
Run the app in development mode:

bash
Copy code
npm start
The app will be available at http://localhost:3000.

Build the app for production:

bash
Copy code
npm run build
Usage Tips
Adding Posts: Fill in the title and body fields in the "Add Post" form to create new blog entries.
Searching Posts: Use the search bar in the header to filter posts by keywords.
Archiving Posts: Toggle "Show archive posts" to view an archive of generated posts.
