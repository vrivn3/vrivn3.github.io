# How to Host a resume online
The purpose of this README is to provide a comprehensive guide on how to effectively host a resume online.
It aims to walk you through the process of hosting your resume on platforms like GitHub, allowing you to create a static website where your resume can be easily accessed and viewed by others

### Prerequisites
- A resume
- A text editor

## Instructions
---
### Formating a resume using Markdown; a lightweight markup language

To format a resume, it's essential to adhere to Andrew Etter's recommendations. This involves choosing a lightweight markup language such as **Markdown**, which offers simplicity and ease of use. When writing content, focus on employing simple syntax and conventions to ensure readability and ease of writing. Additionally, utilize tools that support the markup language for editing and rendering, enhancing the overall document creation process

Here we will be using **visual code studio** as a text editor. Follow the steps bellow

1. **Choose a Text Editor**: Select a text editor of your choice such as Notepad (Windows), TextEdit (Mac), or Visual Studio Code. Ensure it supports Markdown syntax highlighting for easier editing. Tutorial to install the text editor can be found [here](#more-ressources).

2. **Create a New Markdown File**: Open your chosen text editor and create a new file. Save it with a meaningful name like `resume.md`.Find a markdown tutorial [here](#more-ressources).

3. **Edit Your Resume Content**: Begin writing your resume content using Markdown syntax within the text editor. You can include headings, bullet points, lists, and other formatting options as needed.

4. **Save Your Changes**: Save the changes to your Markdown file.

5. **Before Uploading to GitHub Pages**:
   - Before uploading it to GitHub Pages, make sure to rename the file to `index.md` for it to be displayed as the main page of your website.

You now have a formatted resume ready to be shared or published on platforms like GitHub.

## Share/host resume on Github; a distributed version control system

To follow Andrew Etter's advice, use Github, a distributed version control system. Create a repository on GitHub to organize your files. Regularly commit changes to track revisions and collaborate.

_A gif of a resume hosted online using Github and formatted with Jekyll website will be shown at the end of the instructions_

### Creating an Account and Repository on Github

**GitHub** is a widely-used platform for developers to collaborate and manage projects. It's also a useful tool for hosting resumes online, providing professionals with improved visibility and control over their resumes. In this guide, we'll outline the simple steps to host a resume on GitHub.

1. **Go to the GitHub website**: Begin by navigating to the GitHub website. Click [here](https://github.com/) to access the platform.

2. **Signing up for an Account**: Click on the **"Sign up"** button located at the top right corner of the page to initiate the account creation process.

3. **Creating Your Account**: Follow the on-screen instructions to enter your credentials and finalize the creation of your GitHub account.

4. **Setting Up Your Repository**:
   - Click on the **"+ (create new)"** sign located at the top right corner of the sidebar on your home account page.
   - Select **"New repository"** from the options provided.
   - Enter your GitHub username in the **"Repository name"** field. This username will serve as the repository name, enabling you to create a dedicated space to host your resume on a static website.
   - Optionally, add a description in the provided **Description** field.
   - Ensure the repository is set to **Public** to make it accessible to anyone.
   - Confirm your selections by clicking on **"Create Repository"** at the bottom of the page.

By following these steps, you've successfully established your presence on GitHub and created a dedicated repository to host your resume.

### Uploading Your Resume

1. **Accessing Your Repository**:

   - Navigate to your GitHub profile page and click on the repository you created for your resume.

2. **Initiating Upload**:

   - locate and click on the **"+"** icon near the green "Code" button. From the dropdown menu, choose **"Upload files"**.

3. **Adding Your Resume**:

   - Click on the **"Choose files"** button to select your resume file from your computer. Alternatively, you can drag and drop the file directly into the designated area.
   - Ensure your resume file is appropriately named **index.md** (Make sure that your resume file is named index.md. This particular filename is essential because GitHub recognizes it as a special file and will display it on your static website accordingly).
   - After selecting the file(s) you wish to upload, click on the **"Commit changes"** button at the bottom of the page.

4. **Verifying Upload**:

   - GitHub will display a progress bar indicating the status of the upload. Once completed, the file(s) will be listed in your repository.

5. **Optional: Adding a Commit Message**:

   - Before committing changes, you may choose to provide a brief description of the upload in the **"Add an optional extended description"** field.

6. **Reviewing Your Repository**:
   - After the upload process is finished, navigate back to your repository's main page. You should now see your resume file listed among the files in your repository.

By following these steps, your resume is successfully uploaded to your GitHub repository.

### Formating the resume with Jekyll; a static site generator

To implement Andrew Etter's advice,we will be choosing **Jekyll** as your static site generator (SSG). We wil be able to customize Jekyll with a theme or adjust its settings according to our preferences. Organize our content into pages or sections within Jekyll for clarity.This works by adding a **\_config.yml** file that will contain our desired theme for formatting the resume.

1. **Creating the Configuration File**:

   - Click on the **"+"** located near the green "Code" button.
   - Select **"Create new file"** from the dropdown menu.
   - Name the file **\_config.yml**.

2. **Configuring the Theme**:

   - In the newly created \_config.yml file, type in: `theme: jekyll-theme-THEME-NAME`, replacing "THEME-NAME" with the name of the Jekyll theme you'd like to use.
   - Supported Jekyll themes can be found [here](https://pages.github.com/themes/).
   - Click on **"Commit changes"** to save the \_config.yml file.
   - GitHub will take some time to apply the selected theme to your resume.

3. **Previewing Your Resume**:
   - In a new window, navigate to your static website page by typing **Github_Username.github.io**. For example, if your GitHub username is "joe," your static website page link will be joe.github.io.
   - This page will display your resume formatted with your chosen Jekyll theme.

By following these steps, your resume will have a professional and visually appealing appearance and will be hosted on you own static website.

![Animated GIF](https://github.com/vrivn3/vrivn3.github.io/blob/main/Gif.gif)
---

## More ressources
- Markdown tutotial [here](https://www.markdowntutorial.com/)
- Installing [Visual code studio](https://code.visualstudio.com/download), a text editor supporting markdown
- Explore Jekyll themes on Github pages [here](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll)
- Find how to make a GIF [here](https://sproutsocial.com/insights/how-to-make-a-gif/).
- Learn why and how to make a README [here](https://www.makeareadme.com/).

## Authors and Acknowledgements

### Authors:
- Saida Sanon

### Acknowledgements:
- Special thanks to Demessie and Yuze Chan for their valuable contributions and collaboration throughout the project.
- We acknowledge the Jekyll theme used in this project, provided by [orderedlist](https://github.com/orderedlist).


## FAQs (Frequently Asked Questions)

### Why is my resume not showing up?
If your resume is not displaying on the static website, make sure that:
- Your repository name is the same as your username.
- Your repository visibility is set to public.

### Why is Markdown better than a word processor?
Markdown offers simplicity and portability compared to traditional word processing software like Microsoft Word. With Markdown, formatting is done using plain text, making it straightforward to learn and use. Additionally, Markdown files are lightweight and can be opened and edited on any operating system with any text editor, ensuring compatibility across different devices and software. This simplicity and portability make Markdown an efficient choice for creating and managing documents, particularly in collaborative and cross-platform environments.



