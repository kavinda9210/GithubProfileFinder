# 🔍 **GitHub Profile Search** 🌐

In this project, we will be developing an interactive **GitHub Profile Search** application using **HTML**, **CSS**, and **JavaScript**. This application allows users to search for GitHub profiles by entering a username. After submitting, an API call is made to fetch and display the user's details, along with their repositories.

---

## 📝 **Prerequisites**:

To follow along with this project, you should have a basic understanding of:

- **HTML** 📄
- **CSS** 🎨
- **JavaScript** 💻

You should also have:

- A text editor (e.g., VSCode) ✍️
- A web browser to run the code 🌐

---

## 🚀 **Approach**:

### 1. **HTML Structure**:
- Create the **GitHub Profile Search** layout using HTML tags. We use the `<input>` tag to allow users to enter the GitHub username they wish to search for.

### 2. **CSS Styling**:
- The entire styling is done through an external **CSS** file. This handles the colors, card layout, alignment, and general appearance of the app to make it visually appealing.

### 3. **JavaScript Functionality**:
- Define the **API URL** and **axios** script in the JavaScript file.
- Store references to HTML elements like the search bar.
- Create a user-defined function named `userGetFunction` to make an API call using the username as the parameter.
- Implement error handling in case the profile is not found.
- Create `repoGetFunction` to fetch the user's repositories and display the first 5 repositories in the card layout.
- Use `userCard` to display user details in a neat card format.
- Use `repoCardFunction` to display the repositories and provide clickable links to each repository.

---

## 🌟 **Features**:

- **Search GitHub Profile**: Search for any public GitHub user by entering their username.
- **Display User Details**: View the user's profile picture, name, username, and other details.
- **Repositories**: The application shows up to 5 repositories from the user, with clickable links to visit each repository.
- **Error Handling**: Handles errors gracefully if the user is not found.

---

## 📸 **Screenshots**:

### 📸 **GitHub Profile and Repositories**:
![GitHub Profile Search](https://github.com/kavinda9210/GithubProfileFinder/blob/main/GithubProfileFinder/screenshot/Screenshot.PNG) *(Update with actual image URL)*

---

## 🛠️ **How to Use**:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/github-profile-search.git
