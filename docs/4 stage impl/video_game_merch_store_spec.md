
# 🎮 Video Game Merch Store — Specification

## 📌 Purpose of the Application

The purpose of the **Video Game Merch Store** is to provide users with a convenient and engaging way to browse and collect merchandise related to their favorite video games.  
It allows users to:

- Discover and organize items into collections  
- Mark favorite goods  
- Explore categorized merchandise by genre and game  

The **Admin Panel** ensures that the catalog stays up-to-date and relevant.  


## 🧭 User Objectives

### Why will users want to use the application?

Users will visit the application primarily to:

- Discover and collect merchandise related to their favorite games  
- Browse by **genre** or **game title**  
- Search for specific items  
- Mark items as **favorites** to revisit later  


## Basic Scenario

1. The user opens the **Home Page** and sees a catalog of game-related merchandise  
2. Uses **filters** (e.g. Game, Genre, Price) to narrow down the results  
3. Selects an item to **view details**  
4. Marks the item as a **favorite**  


## Advanced Scenario

1. A returning user **logs in**  
2. Opens their personal **Favorites** collection  
3. Compares items using sorting (by **popularity** or **price**)  
4. Discovers a new product via **genre filter** and adds it to favorites  
5. Logs out or continues browsing  


## 🖼 Interface Pages

### 📄 1. Home Page (Public)

- **Header**: App name, Login / Register buttons  
- **Hero Section**: Featured items or categories  
- **Filter Sidebar**:  
  - Genre  
  - Game  
  - Price  
  - Popularity  
- **Product Grid**:  
  - Image  
  - Name  
  - Price  
  - 💖 Add to Favorites  


### 🔍 2. Product Details Page

- Product Image  
- Name, Description  
- Genre, Game  
- ⭐ Rating  
- 💖 Add to Favorites (if logged in)  
- 🔙 Back to Catalog  


### 3. Login Page

- Email  
- Password  
- 🔓 Login Button  
- Link to **Register**  


### 4. Register Page

- Email  
- Password  
- Confirm Password  
- 📝 Register Button  


### 5. Favorites Page (Logged-in Users Only)

- List of **Favorited Items**  
- Sort by:  
  - Price  
  - Name  
  - Popularity  
- ❌ Remove from Favorites Button  


### ⚙️ 6. Admin Dashboard

- **Navigation Menu**:  
  - ➕ Add Product  
  - ✏️ Edit Product  
  - 🗑️ Delete Product  
- **Product Table/List**:  
  - Product Name  
  - Actions: Edit / Delete  
