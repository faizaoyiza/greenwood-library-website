# greenwood-library-website

# 🧪 Capstone Git Project: Greenwood Community Library Website

## 📘 Overview  
This project simulates collaborative development using Git and GitHub for a fictional website called **Greenwood Community Library**. Two contributors, **Morgan** and **Jamie**, worked on separate features using branches and pull requests. Morgan added a new `Book Reviews` section, while Jamie updated the `Events` page with upcoming events.

## 🔧 GitHub Repository URL  
[GitHub Repository: greenwood-library-website](https://github.com/faizaoyiza/greenwood-library-website)
## ✅ Part 1: Setup and Initial Configuration

### 1. Install Git  
To start, I installed Git from the official website: [https://git-scm.com](https://git-scm.com) and confirmed the installation with:

```bash
git --version
```

### 2. Create GitHub Repository  
- I created a new repo on GitHub named `greenwood-library-website`.  
- I initialized it with a `README.md`.  
- Then I cloned it to my local machine using:

```bash
git clone https://github.com/faizaoyiza/greenwood-library-website.git
```
<img width="896" alt="Image" src="https://github.com/user-attachments/assets/7c111a63-756e-4f57-8e9b-b020b9c2fbc3" />
### 3. Set Up Initial Website Files  
Inside VS Code, I created the following HTML files with placeholder content:
- `home.html`
- `about_us.html`
- `events.html`
- `contact_us.html`
<img width="959" alt="Image" src="https://github.com/user-attachments/assets/1f0c1ecd-9860-42f6-90bf-dfb14ab1999e" />
Then I staged and committed them to the `main` branch:
<img width="911" alt="Image" src="https://github.com/user-attachments/assets/2801a5d5-d7ce-4b02-8128-26e26ef84e2a" />
## 👩‍💻 Morgan's Work: Add Book Reviews Section

### 1. Create and Switch to a New Branch   Stage, Commit, and Push Changes  
```bash
git checkout -b add-book-reviews git add book_reviews.html
git commit -m "Add book reviews section"
git push origin add-book-reviews
```
<img width="798" alt="Image" src="https://github.com/user-attachments/assets/21201e98-1232-4531-803c-1386af1054f9" />
### 2. Add New File  
I created `book_reviews.html` and added random placeholder content.
<img width="959" alt="Image" src="https://github.com/user-attachments/assets/677b5237-caee-4c13-8a93-32db2006c6af" />
 


### Create Pull Request  
I opened GitHub and created a pull request from `add-book-reviews` to `main`, then **merged** it after reviewing.

## 🧑‍💻 Jamie's Work: Update Events Page

### Create and Switch to Branch  
```bash
git checkout -b update-events
```
### Update the File  
Edited `events.html` to include upcoming community events.

### Stage and Commit the Changes  
```bash
git add events.html
git commit -m "Update events page with upcoming events"
```
### Push the Branch  
```bash
git push origin update-events
```
<img width="946" alt="Image" src="https://github.com/user-attachments/assets/e77ebed3-19d2-4c75-9b69-f9c4c2aabfae" />
### 5. Create Pull Request  
Followed the GitHub link to create a pull request from `update-events` to `main`. Pulled latest changes and then **merged** the PR.
