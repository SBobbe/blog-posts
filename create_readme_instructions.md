# Creating a README File in a Github Repository

## *A guide for setting up a docs-as-code workflow*

### Table of Contents

* Who, what, when, where, and why Docs-as-Code?
* Vocabulary and getting your bearings
* Before you begin
* Step-by-step instructions
* Tips for writing in Markdown
* Create your own notes guide
* Review and Commit (to streamlined documentation!)

## Who, what, when, where, and why Docs-as-Code?

| Who?                                                                                                                            | What?                                                                                                | When?                                                                                                                       | Where?                                                                                                                                                | Why?                                                                                                                                           |
|---------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| You! In addition, anyone from developers to technical writers to the end user uses documentation to stay current on the project | Docs-as-Code means using the same tools and workflow that developers use to write and publish code.  | Projects that grow and change quickly require nimble documentation to ensure stakeholders can access accurate information!  | Your Docs-as-Code setup will require a text-editor, a version-control system, a Static Site Generator, a CI/CD pipeline, and a web hosting platform.  | Adopting Docs-as-Code will allow you and your team to collaborate more easily with more stakeholders and streamline the documentation process. |
___

## Vocabulary and getting your bearings

* **Version Control System**: A website or app that allows you to track changes to a project. We'll be using **Git** for our project.
* **Git**: a Version Control System that tracks changes, allows synchronous collaboration, and lets you revert changes.
* **Github**: A Git web platform that hosts your projects online. You can also share your projects with others.
* **Github Desktop**: An app that lets you manage your **repositories** from your desktop
* **Repository**: Where all of your Git projects are stored, including their entire history.
* **Homebrew**: A tool used in OS to download **VSCode**
* **Visual Studio Code**: VSCode is the relatively easy-to-use code editor we'll use to creat your first **README** file.
* **README**: a README file contains a brief overview of any relevent information about a project. In software technical writing, you may see README.md; the "md" indicates that the file is written in **Markdown**.
* **Markdown**: a language usable in plain-text editors to format text on web platforms, as well as to write documentation.
* **Commit, Publish, Push**: These verbs describe the process of moving your file from your local repository to Github online.

If you are feeling confused about how all of these pieces fit together, and learn best from analogies, read on! (will update later) If you've got this and are ready to create your first README.md file, scroll down to **Before you begin** to get started.

## Before you begin

Before you can create your new README.md file, you'll need to do a little computer housekeeping first.

1. Create an account on the Github website. This will host your remote repository.

2. Download and install Github Desktop and Visual Studio Code (VSCode) from their websites.

3. Install Homebrew for MacOS

4. Install Git using Homebrew

2. Finally, we'll create a home for your local repository. If you're in MacOS, use Finder to open your User folder (often labeled with your name) and create a new folder called "Repositories".

You're all set to begin creating repositories and publishing to Github--you'll only need to do this setup once on your computer. We'll be extra efficient and create your first README.md file in a repository that's dedicated to your learning notes.

## Step-by-step instructions

1. First, we'll need to create the infrastructure that will move your projects from your local repository to the Github website. Log in to the Github website. On the homepage, click **Create New Repository**. Let's name our new repository "Notes" and keep it private for now.

2. Open Github Desktop and find your "Notes" repository. Select this repository and **clone** it to your Repositories folder that you created in your User folder. By cloning it, you have just created a local copy of your repository for you to work on on your desktop. When you're finished, you'll be able to push your changes back to the remote repository (Github). You're ready to create your first file!

3. Open VSCode and find your "Notes" repository. Click on the "New File" icon and name your new file "README.md" Congratulations, you're ready to write! Let's write a README file that will give you instructions in your own words to replicate what you've just done for your next project.  

>## Tips for writing in Markdown
>Writing simply-formatted text is easy in Markdown, and you'll get the hang of it quickly. Check out this [cheat sheet](https://www.markdownguide.org/cheat-sheet/) to learn basic formatting skills, such as creating headers and lists. If you'd like to create a table, use this [Markdown table generator](https://www.tablesgenerator.com/markdown_tables#). But don't take my word for it--there are plenty of resources online with very specific answers to very specific questions. There are also plugins (sometimes called "linters") that will review your Markdown for errors and help you fix them.
>
## Create your own notes guide

Now that you're ready to work on your own projects, let's write that how-to guide for your later reference.

4. In your README.md file, create a header by typing "# How to Create, Push, and Publish Markdown Files" at the beginning of a new line.
5. Create a subheader in a new line by typing "## A step-by-step guide". Practice creating numbered lists beneath this subheader by typing "1. 2. 3. "etc.

6. Using subheaders and a numbered list, format the following text and fill in the blanks to create an easily-readable how-to guide for how to create and publish a Markdown file using Github, Github Desktop, and VSCode. Feel free to link in any useful resources you'd like to bookmark by using the format [link text](link url):

> First, create a new repository on the ______website. You'll need to give it a title and decide whether it will be public or private. Next, open Github desktop and find your repository. You'll need to ______ it in order to move it between your local repository and the remote _________ on Github. Open _________ and click on __________. You'll need to create a new file and name it with the title and ___ as the file type. Now you're ready to work in your new file.

7. Great work! We're almost done--it's now time to commit, push, and publish your doc to the Github website. Go ahead and save your file in VSCode and document in your how-to guide that you have done so.

> [!IMPORTANT]
> VSCode will *not* save your file automatically--be sure to save frequently and leave yourself a note in your guide as a reminder. You can use the following formatting to help your reminder stand out.

! [Image shows different ways to format information you would like to emphasize](file:///var/folders/j4/gg7s8wtx3sj2jxnggvktwg_c0000gn/T/TemporaryItems/NSIRD_screencaptureui_6RCbAK/Screenshot%202024-07-29%20at%204.50.35%E2%80%AFPM.png)
If you'd like to see how this formatting looks once published, click [here](https://github.com/orgs/community/discussions/16925).

8. Open Github Desktop. You should see your README.md file open in your "Notes" repository. Find two text boxes above the "Commit to **main**" button. Type README.md in the title field and in the description field write "Created a guide for publishing .md files." Document these steps in your how-to guide and save in VSCode again. Then, hit "Commit to Main."
9. The next step, which you can include in your guide before you save it again, is to press the "Publish branch" button at the top of the screen. This will publish what you've worked on from your local repository to the remote one.
10. Great job, you've done it! Go ahead and press the "View on Github" button or go directly to the Github website to see your finished project. After any changes you make to your guide, remember to save in VSCode, give a summary of changes and description in Github Desktop, and commit and push your updates.
