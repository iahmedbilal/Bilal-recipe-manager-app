# 📘 Recipe Manager App

A simple and responsive recipe manager built with **HTML, CSS, and JavaScript**.  
Users can add, view, edit, delete, and search recipes. All data is stored in **localStorage**.

## 🚀 Live Demo
https://iahmedbilal.github.io/Bilal-recipe-manager-app/

## 🧩 Features
- Add, edit, and delete recipes
- Search by title
- Filter by difficulty (All / Easy / Medium / Hard)
- Optional filter: max prep time
- Clean detail view with image, ingredients, and steps
- Fully responsive layout (mobile + desktop)
- Data saved locally in the browser

## 💾 Data Structure in LocalStorage Structure
Each recipe is stored under:

"recipes"

as

{

  "id": "unique-id",
  
  "title": "Recipe Name",
  
  "difficulty": "Easy",
  
  "prepTime": 10,
  
  "cookTime": 15,
  
  "imageUrl": "path_or_url",
  
  "description": "Short intro",
  
  "ingredients": [...],
  
  "steps": [...]
  
}

## ⚙️ How to Run the app
### Option 1 – Open Directly :

-Download the project

-Open index.html in any browser

### Option 2 – VS Code Live Server (Recommended) :

-Install Live Server extension

-Right-click index.html → Open with Live Server


## 📌 Assumptions & ⚠ Limitations
- Works only in modern browsers
- localStorage clears if browser data is wiped
- Broken image shown if incorrect URL is used

## 🛠 Known Issues
- Ingredients and steps are text-based (one per line)
- No authentication or cloud sync

 ## 📸 Screenshots

Below are screenshots of the Recipe Manager App:

### Home Page :
<p align="center">
  <img src="/home.png" width="50%">

### Add Recipe Page :
  <p align="center">
  <img src="/add.png" width="50%">

 ### Recipe Detail Page :
  <p align="center">
  <img src="/detail.png" width="50%">
</p>

