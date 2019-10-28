# How to Host Your Resume Using GitHub Pages

### Who is this Made For?
This is written for those who have none to minimal experience with GitHub, Jekyll, Atom or Markdown.

### What do you need?
You will need to have a few things in order to get started:
1. A computer with available hard drive space.
2. A current Email address.
3. A resume
4. A basic understanding of computers.
5. Some patience.

### How do you do it?
#### Make a GitHub Account
To start things off, you will need to make a GitHub account.  

Step 1: Go to [GitHub](https://www.github.com).  
A front page will come up with a prompt for signing up.   

Step 2: Sign up for GitHub Pages.  
There will be two options for account types: free or paid. You will only need the free version, but the paid subscription works if you so choose.

#### Install Atom
Next up, you will need Atom installed on your computer.  

Step 1: Go to [Atom's Website](https://atom.io).  
There will be a large button center screen prompting you to download.  

Step 2: Download Atom.  
Click the large download button to begin the download process.

Step 3: Install Atom.  
The installation process is (relatively) quick and simple. Follow the atom installer's prompts, and atom will be installed and ready in no time at all.

#### Create your Resume
To get things started you're going to want to convert your resume into a markdown file.  

Step 1: Open Atom.  
Navigate to wherever you downloaded Atom to (likely your desktop) and open Atom. Atom is quite large and may take a few seconds to open. If this is your first time opening Atom, the program will walk you through some beginner steps. 

Step 2: Create a new file.  
Click the file tab at the top left of your page and click the new file button.  

Step 3: Convert your resume into markdown.  
If you're familiar with markdown, this step shouldn't take long. If this is your first time hearing of markdown or just need some practice, visit this [Markdown Tutorial.](https://www.markdowntutorial.com)  

Step 4: Save the resume file as "index.md".  
This naming convention is necessary for applying a Jekyll theme later.  

#### Host your Resume on GitHub
Once you have your resume in markdown, it's time to start using your GitHub account. There are a few steps you'll need to take in order to host your resume. Many of these steps will be broken up into sub-steps, as the process can be quite complex.

##### Step 1: Make a Repository
You will need to contain all necessary files in a repository in order to host your resume. Here, we will briefly go over the process of creating a repository.

Step 1: Begin the creation process.  
On the left side of your GitHub home page, you can click the link that says, "Create a new Repository". Click this link and a new page will open where you create the repository.  

Step 2: Name the repository.  
From here, you should input a meaningful repository name, as this will be publicly viewable. If you would like to eliminate ambiguity down the line, name the repository "[your GitHub name].github.io".

Step 3: Finalize your repository. You can add a description if you would like, but it isn't necessary. Leave your repository as public, as you can't host a site if it's private. From here, you can choose to initialize with a README, although this tutorial won't cover the README's usage. Finally, hit the green "Create Repository" button and finish creating your repository!

##### Step 2. Add your Resume to the Repository
In order to host a resume using GitHub, it will have to be uploaded to a repository.  

Step 1: Navigate to your repository on GitHub.  
From the home page, click on the repository that you plan on using, located on the left of the page.  

Step 2: Upload your resume.
On the repository's code page, you will find three grey buttons around the center of the page. Click the one that says, "Upload Files".  
On the following page, you have two choices for how to upload your file: you can click and drag your file to the page, or you can "choose your files" from the link in the center of the page. Add your index.md file from wherever it's located with whichever method you prefer.  

Step 3: Commit your changes.  
Feel free to add a commit message if you would like in the space provided. It should just be a short description of what you did. Then click "Commit Changes". Your resume is now on GitHub!

##### Step 3. Host your Resume and Add a Jekyll Theme  
Adding a Jekyll theme is a great way to add some flare to your resume. The following instructions will describe how exactly to add a theme using GitHub's theme chooser.  

**WARNING:** Some Jekyll themes are not formatted to handle tables. If you use tables in your resume, preview your theme before you send out your link, as the table may be broken. 

Step 1: navigate to the settings tab of your repository.  
This tab is located near the top of the screen, a little right of center. Click on it once you've located it.

Step 2: Navigate to the "GitHub Pages" settings.  
Once in the settings menu, scroll downward until you get to the "GitHub Pages" area. Here, you'll see a few options depending on the name you gave your repository. If you followed the repository naming convention specified earlier, skip to step 4.

Step 3: Change your source branch.  
In order to get your resume actually hosted on a site, click the drop-down bar below the "Source" tab and select the master branch. Provided you haven't added any extraneous folders, your resume will be hosted online.  


Step 4: Add the theme.  
Once the site is hosted, go to the Theme Chooser and click the "Choose a Theme" button. You Will be redirected to a new page with a bunch of different themes on display. Take some time to find a theme that you like. Once you've set your mind on one, click "Select Theme". Now your resume has a them that you can view by clicking the link at the top of the "GitHub Pages" area of settings.

##### Step 4. Modify Your Jekyll Theme with Frontmatter
Now that your resume has a theme, we can modify the theme to make it a little more personal to you.  

Step 1: Go to your configuration file.  
Navigate back to your code tab in your repository. Now you'll find that there is a new file in your repository named "\_config.yml". Click on this file name to open it. Once on this page, click the pencil icon in the middle right of the screen to edit the text.

Warning: In the \_config.yml file, there will likely be only one line that says "theme: \[ _your theme name_ \]". Do not modify this line, as your theme will no longer display properly.

Step 2: Add a title to your theme.  
Add a new line to the file without changing any existing ones. In this line, write "title: [ _your title here_ ]", minus the brackets. Whatever you type here will be added to your resume them in the title slot.

Step 3: Add a description to your theme.  
In order to add a description to your theme, follow the same steps as with the title. This time, however, instead of typing "title:", type "description:". On the same line, write out whatever kind of description you would like to add to your resume.  

Step 4: Commit your changes.  
In order to add theses fields to your resume page, scroll down to the bottom of the page and click "Commit Changes". Now your page's title and description will be added to your theme.

Give GitHub a few minutes to update everything before you try viewing your site again, as it may take a while to update. If you're not happy with how your theme looks, the title or the description, they can all be changed again following the same steps.

Congratulations! Your resume is now finished and being hosted on GitHub pages!


### Where can you get more help?
If you would like to learn more about Jekyll, check out [Mike Dane's Jekyll tutorials](www.https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB).  

If you're looking for more markdown help, GitHub has a tutorial [available here](https://guides.github.com/features/mastering-markdown/).  

If you would like more information on GitHub pages and hosting static websites, here's a few resources.
- [GitHub's tutorial on pages](https://guides.github.com/features/pages/)
- [ProgrammingKnowledge2's video tutorial](https://www.youtube.com/watch?v=nqXWfXNc0gs)
- [OSTraining's Beginners Guide to Gi tHub Pages](https://www.ostraining.com/blog/coding/github-pages/)


### Who helped make this?
Special thanks to my group members Jordan Portz and Risto "Riki" Zimbakov for their assistance in creating my resume and web pages. Credit to Matt Graham for creating the theme that I used on my resume.

### Any more questions?
Here are some frequently asked questions (FAQs) if you need any extra help.  

Q. Can I further modify my resume theme's looks?  
A. Yes. You can modify the theme's CSS to change it's looks. However, the method detailed above does not support this. If you would like a more customizable experience, follow [Mike Dane's Jekyll tutorials](www.https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB) and reference [Jekyll's documentation](https://jekyllrb.com/docs/themes/) for a more in depth method of site generation.

Q. Why has my README.md's theme changed and not my resume?
A. The README's theme changed, likely, because your resume is not named "index.md". Change the resume's file name by clicking the filename in the code section of your GitHub, clicking the pencil icon, then changing the filename near the top of the page. Reload your webpage and check to make sure the theme has been applied properly.
