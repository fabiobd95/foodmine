1. Create Angular App
    1. Create project's folder
    2. Install @angular/cli
    3. Create App as frontend

2. Add Header
    1. Generate Component
    2. Add HTML
    3. Add CSS

3. List Foods
    1. Create Food model
    2. Create data.ts
        1. Add sample foods
    3. Add images to assets
    4. Create Food service
    5. Create Home component
        1. Add ts
        2. Add HTML
        3. Add CSS

4. Search
    1. Add method to Food service
    2. Add search route
    3. Show search result in Home component
    4. Generate search Component
        1. Add to home component
        2. Add ts
        3. Add HTML
        4. Add CSS

5. Tags Bar
    1. Create Tag model
    2. Add sample tags to data.ts
    3. Food service
        1. Add get all tags method
        2. Add get all foods by tag method
    4. Add tags route
    5. Show tag result in Home component
    6. Generate Tags component
        1. Add to home component
        2. Add ts
        3. Add HTML
        4. Add CSS

6. Food Page
    1. Add method to food service
    2. Generate Food Page component
        1. Add Route
        2. Add ts
        3. Add HTML
        4. Add CSS

7. Cart Page
    1. Create CartItem Model
    2. Create Cart Model
    3. Generate Cart service
    4. Add to Cart Button in Food Page
    5. Generate Cart page component
        1. Add Route
        2. Add ts
        3. Add HTML
        4. Add CSS

8. Not Found!
    1. Generate Component
        1. Add ts
        2. Add HTML
        3. Add CSS
    2. Add to Pages
        1. Home Page
        2. Food Page
        3. Cart Page

9. Connect To Backend
    1. Create backend folder
    2. npm init
    3. npm install typescript
    4. Create tsconfig.json
    5. Create .gitignore
    6. Copy data.ts to backend/src
    7. npm install express cors
    8. Create server.ts
        1. install @types
        2. Add APIs
    9. npm install nodemon ts-node --save-dev
    10. Add urs.ts to frontend
    11. Add HttpClient module
    12. Update food service