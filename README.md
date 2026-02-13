# Lost After the Crash – Survival Adventure

## Description

This project is an interactive survival story inspired by the classic "Choose Your Own Adventure" format. The player wakes up after a plane crash on a mysterious island and must make decisions to survive.

Each decision leads to a different HTML page, allowing the user to explore multiple paths and reach different endings depending on their choices.

The story includes:

- A good ending
- A neutral ending
- A bad ending

The entire project was built using only HTML, without JavaScript or CSS.

---

## How It Works

The story begins at:

index.html


From there, the player navigates through different pages using standard HTML links (`<a>` tags). Each page presents at least two choices, and each choice leads to a different HTML file.

All files are organized inside the following structure:

html/
│
├── index.html
├── paginas/
│ ├── selva.html
│ ├── avion.html
│ ├── rio.html
│ ├── montana.html
│ ├── cueva.html
│ ├── fuego.html
│ ├── senal.html
│ ├── noche.html
│ ├── final_bueno.html
│ ├── final_neutro.html
│ └── final_malo.html
│
└── assets/
├── images used in the story


Each HTML file contains:

- `<head>`, `<body>`, and `<footer>`
- At least one heading (`<h1>`)
- At least one paragraph (`<p>`)
- One image related to the scene
- Text formatting tags such as `<b>`, `<strong>`, and `<small>`
- At least two navigation links (`<a>`)

---

## How to Run the Project Locally

### Option 1: Open Directly

1. Navigate to the `html` folder.
2. Open `index.html` in your browser.

### Option 2: Using NGINX

1. Make sure NGINX is installed and running.
2. Copy the project files to:

/var/www/html/adventure


3. Set proper permissions:

sudo chmod -R 755 /var/www/html/adventure


4. Open your browser and go to:

http://localhost/adventure/
---

## Technologies Used

- HTML
- NGINX
- Git

No JavaScript or CSS was used in this project.

---

## Author

Diego Alejandro Quan Castillo  
Universidad del Valle de Guatemala  
Web Systems and Technologies – Lab 2
