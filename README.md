
#  RecipeVault – A Django-Based Recipe Sharing Platform

RecipeVault is a modern and user-friendly web application built using **Django**, designed for users to **create, share, and explore recipes**.
It features user authentication, recipe management, comments, ratings, profile management, and a clean Bootstrap-based interface.

---

##  Features

###  **User Accounts**

* User registration & login
* Personalized dashboard
* Edit profile details

###  **Recipe Management**

* Add new recipes with:

  * Name
  * Image
  * Description
  * Ingredients
  * Instructions
  * Cooking time
* Edit and delete your own recipes
* View any user’s recipes
* Responsive card-based layout

###  **Ratings & Reviews**

* Rate recipes (1–5 stars)
* Post and read comments
* Average rating displayed on recipe detail page

###  **Media Handling**

* Recipe images stored in `/media/`
* Django Media settings configured

###  **Clean UI**

* Bootstrap-based interface
* Card layout for recipe gallery
* Simple and responsive design

---

## Tech Stack

| Component           | Technology                |
| ------------------- | ------------------------- |
| **Backend**         | Django 5.x                |
| **Frontend**        | HTML, CSS, Bootstrap      |
| **Database**        | SQLite3                   |
| **Server**          | Django development server |
| **Version Control** | Git & GitHub              |

---

##  Project Structure

```
ADSD-Medha_Final_Project/
│
├── core/                     # Main project settings
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── myrecpies/                # Main application
│   ├── templates/            # HTML templates
│   │   ├── base.html
│   │   ├── card.html
│   │   ├── profile.html
│   │   └── recipedetail.html
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── migrations/
│
├── static/                   # CSS, JS, images (optional)
├── media/                    # Uploaded recipe images
│
├── manage.py
└── README.md



##  How to Use

1. Create an account or log in.
2. Add your recipes using the form.
3. View your recipes in the **My Recipes** section.
4. Browse other users’ recipes.
5. Rate recipes and leave comments.
6. Edit or delete recipes you created.

