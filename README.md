# Microsoft Website Clone

This is a frontend clone of the Microsoft website built using **Tailwind CSS**. The project replicates the layout and styling of the official Microsoft website.

## 📌 Technologies Used
- **HTML**
- **Tailwind CSS**

## 📂 Project Structure
```
📁 microsoft-clone
│── 📜 index.html       # Main HTML file
│── 📜 style.css        # Custom CSS file
│── 📜 tailwind.config.js # Tailwind configuration
│── 📜 postcss.config.js  # PostCSS configuration
│── 📜 package.json      # Project dependencies
│── 📜 package-lock.json # Dependency lock file
│── 📜 .gitattributes    # Git configuration
│── 📜 README.md        # Project documentation
```

## 🎯 Getting Started
### 1. Clone the Repository
```sh
git clone https://github.com/poshithNandyala/microsoft-clone.git
cd microsoft-clone
```

### 2. Install Dependencies
If using Tailwind locally, install dependencies:
```sh
npm install
```

### 3. Run a Development Server
Since the project uses Tailwind CSS, it's best to run it on a local server. Use the following command:
```sh
npx tailwindcss -i ./style.css -o ./dist.css --watch
```
Then, you can open `index.html` in your browser.

Alternatively, you can use **Live Server** if you have VS Code:
1. Install the **Live Server** extension.
2. Right-click `index.html` and select **Open with Live Server**.

## 🔧 Customization
You can customize the styles by modifying the Tailwind classes in `index.html` or updating `style.css`.

## 🤝 Contributing
If you’d like to contribute to this project, feel free to submit a pull request.

## 📜 License
This project is for educational purposes only and is not affiliated with Microsoft.

---
**Developed by Poshith Nandyala**
