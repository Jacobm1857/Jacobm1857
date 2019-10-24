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
Step 1: Go to [GitHub](https://www.github.com). A front page will come up with a prompt for signing up.   
Step 2: Sign up for GitHub Pages. There will be two options for account types: free or paid. You will only need the free version, but the paid subscription works if you so choose.

#### Install Atom
Next up, you will need Atom installed on your computer.  
Step 1: Go to [Atom's Website](https://atom.io). There will be a large button center screen prompting you to download.  
Step 2: Download Atom. Click the large download button to begin the download process.  
Step 3: Install Atom. The installation process is (relatively) quick and simple. Follow the atom installer's prompts, and atom will be installed and ready in no time at all.

#### Create your Resume
To get things started you're going to want to convert your resume into a markdown file.  
Step 1: Create a new file. Click the file tab at the top left of your page and click the new file button.  
Step 2: Convert your resume into markdown. If you're familiar with markdown, this step shouldn't take long. If this is your first time hearing of markdown or just need some practice, visit this [Markdown Tutorial.](https://www.markdowntutorial.com)  
Step 3: Save the resume file as "index.md". This naming convention is necessary for applying a Jekyll theme later.  

#### Host your Resume on GitHub
Once you have your resume in markdown, it's time to start using your GitHub account. There's a few steps you'll need to take in order to host your resume.
##### 1. Make a Repository
The first step to hosting a resume is creating a new repository. On the left side of your GitHub home page, you can click the link that says "Create a new Repository" to do as the link says. From here, you should input a meaningful repository name, as this will be publicly viewable. You can add a description if you would like, but it isn't necessary. Leave your repository as public, as you can't host a site if it's private. From here, you can choose to initialize with a README, but it's not necessary. Finally, hit the green "Create Repository" button and finish creating your repository!

##### 2. Add your Resume to the Repository
Adding your resume to your repository is quite simple. Navigate to your repository on GitHub. On the repository's code page you will find three grey buttons around the center of the page. Click the one that says "Upload Files".  
On the following page, you have two choices for how to upload your file: you can click and drag your file to the page, or you can "choose your files" from the link in the center of the page. Once you've selected your "index.md" file, you can commit your changes. Feel free to add a commit message if you would like, then click "Commit Changes". Your resume is now on GitHub!

##### 3. Add a Jekyll Theme  
In order to add a Jekyll theme, navigate to the settings tab of your repository. This tab is located near the top of the screen, a little right of center.  
Once in the settings menu, scroll downward until you get to the "GitHub Pages" area. Here there are two options that you'll have to use:
1. Source
2. Theme Chooser

In order to get your resume actually hosted on a site, click the drop down bar below the "Source" tab and select the master branch. Now your resume will be hosted online.  
Once the site is hosted, go to the Theme Chooser and click the "Choose a Theme" button. You Will be redirected to a new page with a bunch of different themes on display. Take some time to find a theme that you like. Once you've set your mind on one, click "Select Theme". Now your resume has a them that you can view by clicking the link at the top of the "GitHub Pages" area of settings.

##### 4. Modify Your Jekyll Theme with Frontmatter  
Now that you have a theme added to your resume, you'll find that there is a new file in your repository named "\_config.yml". If you open this file, there will likely be only one line that says "theme: \[ _your theme name_ \]". You can modify this file to change some aspects of the theme by clicking the pencil icon on the gray tool bar. Most, if not all, themes allow you to add title and description fields to the frontmatter.

To add a title and a description to your resume theme, begin editing the \_config.yml file. Once you are editing the file, add a new line under the theme line. (Aside: Make sure not to modify the theme line, as you may stop your theme from appearing at all.) On this line, write "title:" (without the quotes) followed by whatever title you want your resume to have. If you would like to add a description to your resume, add another line underneath and write "description:". You can write a short description here.

In order to add theses fields to your resume page, scroll down to the bottom of the page and click "Commit Changes". Now your page's title and description will be added to your theme. Give GitHub a few minutes to update everything before you try viewing your site again, as it may take a while to update. If you're not happy with how your theme looks, the title or the description, they can all be changed again following the same steps.


### Where can you get more help?
If you would like to learn more about Jekyll, check out [Mike Dane's Jekyll tutorials](www.https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB).

### Who helped make this?
Special thanks to my group members Jordan Portz and Risto (Riki) Zimbakov. for their assistance in creating my resume and web pages. Credit to Jon Rohan for creating the theme that I used on my resume.

### Any more questions?
Here are some frequently asked questions (FAQs) if you need any extra help.  

Q. Can I further modify my resume theme's looks?  
A. Yes.

Q. Why has my README.md's theme changed and not my resume?
A.
