# IT IS YESIK BIL NEWS
This code represents a structured news website for a school (Yesik BIL News) with various interactive and functional features that enhance both usability and accessibility. Here are the key features that make it worth looking into:  

1. **Thematic Design & Dark Mode Support**  
   - The site has light and dark themes, allowing users to toggle between them.  
   - Uses CSS classes like `.dark-theme` to modify styles dynamically.  
   - Improved readability with contrasting colors.  

2. **Responsive & User-Friendly UI**  
   - Uses a flexible layout with `.container` elements for content structuring.  
   - Navigation bar with multiple sections such as Главная, Школа, События, Академические Новости, Спорт, Контакты.  
   - Uses media queries indirectly via CSS styling to ensure responsiveness.  

3. **Interactive News Articles with "Read More" Feature**  
   - Each news article has a "Подробнее" button.  
   - Clicking expands the full content using the `toggleInfo()` JavaScript function.  
   - Prevents clutter while keeping the homepage clean.  

4. **Authentication System (Login & Account Creation)**  
   - Users can log in or create an account.  
   - Uses input fields for username and password with a login button.  
   - JavaScript functions like `login()` and `createAccount()` handle authentication.  

5. **Admin Settings & User Customization Panel**  
   - A settings panel allows users to increase or decrease font size and switch between light and dark modes.  
   - Implemented via a floating settings icon that toggles visibility.  

6. **Event & News Sections for School Activities**  
   - Contains detailed school news and upcoming event schedules.  
   - Examples include debate topics, academic updates, and extracurricular activities.  
   - Features event recaps such as chess tournament results with participant names.  

7. **Dynamic JavaScript Functionalities**  
   - `toggleInfo()` expands and collapses detailed news content.  
   - `toggleSettings()` shows or hides the settings panel.  
   - `increaseFontSize()` and `decreaseFontSize()` adjust font size dynamically.  
   - `toggleTheme()` enables dark mode.  

8. **Multimedia Integration**  
   - Uses an image banner in the `#showcase` section.  
   - Supports embedded images such as chess tournament and event posters.  

9. **Structured & Expandable Codebase**
   - Uses semantic HTML elements for easy readability such as `<section>`, `<article>`, `<header>`, and `<footer>`.  
   - Organized CSS rules for scalable design.  
   - JavaScript is implemented efficiently for dynamic behaviors.  

Why is this code worth looking into?  

1. Good for beginners and intermediate developers as it implements a real-world project with UI and UX improvements while showing how to structure a news website effectively.  
2. Scalable and customizable with the potential for additional features such as user authentication via a database and API integration.  
3. Practical for school websites and news portals as schools can use this as a news management system and evolve it into a full-fledged blogging or educational platform.  
4. Strong user engagement with dark mode, font adjustments, and an interactive settings panel that enhances usability. Expanding news articles keeps the homepage uncluttered while providing depth.  

This project blends aesthetics with functionality, making it a great reference for developing a modern school news website. If integrated with a backend, it could become a fully operational platform for sharing school updates dynamically.
