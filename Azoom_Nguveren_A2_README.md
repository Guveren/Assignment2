# How to host your resume on GitHub Pages

Github is a repository hosting service for software development deployed through Git which is a version control system. With GitHub, we can host portfolios/blogs, projects or websites directly from a repository on gitHub.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
Essentially, our mission here is to host a resume on a GitHub page. Further down below, are step by step guidelines on how to accomplish this task.

## Audience
This is intended for individuals with no prior knowledge with GitHub or Git, Jekyll, Markdown and little experience using atom. It focuses on a plain approach to familiarize individuals with these tools to improve technical communication in the tech community.
### 1.0. Prerequisites
Some of items we will need to achieve hosting a resume on a GitHub page is listed as follows:  

* A Resume *written in markdown*
* Text Editor (*In this case, we will be using* Atom)
* GitHub account
  > * Sign into your GitHub account here [GitHub Sign-in](https://github.com/login ) using your GitHub account details.  
  > * If you do **NOT** have an account, you could create an account by signing up here [Join GitHub](https://github.com/join)

* GitHub repository  
  Here's how to **create a GitHub repository**
  > 1. Once you are logged in, to get started, create a new repository by clicking on the **+** Drop-down menu located at the top-left corner and select the option **New repository**.  ![image_1](https://github.com/Guveren/Assignment2/blob/master/images/image_2.png)
  > 2. Enter your desired repository name in the provided text-box for the repository name preferably short and memorable.  ![repName](https://github.com/Guveren/Assignment2/blob/master/images/repName.png)  
  > 3. This is optional, but you could type in a description of the repository like "Host a resume" ![image_2](https://github.com/Guveren/Assignment2/blob/master/images/image_3.png)
  > 4. Depending on your preference, you can decide to make the repository **private** or **public** by selecting one  of the radioButtons.![image_3](https://github.com/Guveren/Assignment2/blob/master/images/image_4.png)
  > 5. Select **Initialize this repository with a README**![image_4](https://github.com/Guveren/Assignment2/blob/master/images/image_5.png)
  > 6. Finally, click on the button **Create repository**.
  >There you have it, you have successfully created a repository.


### 1.1. Installing
Here, our text editor of interest is Atom. Thus we need to ensure that we have the required IDE(*Integrated Development Environment*). If you do not have Atom IDE, you will need to install it.
> To install the Atom IDE, visit: [https://flight-manual.atom.io/getting-started/sections/installing-atom/](https://flight-manual.atom.io/getting-started/sections/installing-atom/).  

  We also will be formatting our resume using Jekyll themes. If you do not have the latest version of Jekyll and ruby, then you will need to install these using terminal.
> To install Ruby and then Jekyll, visit: [https://jekyllrb.com/docs/installation/](https://jekyllrb.com/docs/installation/)


## Deployment

Assuming that we have all we need to begin, let's make sure that the resume file we are editing is written via markdown and has the filename extension  ""**.md**"". Why?  Not only is Markdown easier to type and read, it is applicable to anyone from developers, designers to even the Non-techies! New to markdown? Here is a link to an awesome and quick tutorial of how to use markdown [Markdown Tutorial](https://www.markdowntutorial.com)

### 2.0. Associating Atom with GitHub
Given that we have created a repository, we are going to connect atom with GitHub and to do this we will first
> 1. Select the **Clone or download** drop-down menu and click on the clipboard button  ![image_7](https://github.com/Guveren/Assignment2/blob/master/images/image_7.png)
> 2. Open atom application and simultaneously click on ```cmd + shift + p ``` to toggle the command palette.
> 3. Type in ```GitHub: Clone```
> 4. Paste the directory or use ```cmd + v```.  ![image_8](https://github.com/Guveren/Assignment2/blob/master/images/image_8.png) to insert the link the GitHub repository and click on the **+Init** button

### 2.1. Staging, Commits and Pushing
While editing our resume, we constantly want to be updating it. This is why we will need to work with committing changes to our resume. Think of this process as a detailed revision of the resume. Here's how we commit changes to the resume.  

Essentially, this is a small snippet of what we will be doing ![gifA](https://github.com/Guveren/Assignment2/blob/master/images/gifA.gif)

### 2.2. Format the resume using Jekyll themes
On the course of formatting our resume, we might want to include  a few additions in order to enhance its visual appeal. We will integrate Jekyll themes into our resume, this is a very simple and quick process.
> 1. While on your GitHub page, navigate your way to the working repository.
> 2. Select the **Settings** button on the top-left of the panel menu.  
> 3. Under the **GitHub pages** panel, click on the **choose template** button.
> 4. Choose a theme and click the green **Select theme** button. ![image_9](https://github.com/Guveren/Assignment2/blob/master/images/image_9.png)

## Additional Resources
* https://www.markdownguide.org/basic-syntax/#line-breaks
* [Creating your own Jekyll Theme](https://medium.com/@jameshamann/creating-your-own-jekyll-theme-gem-1f8180a0e4b8)

## Authors and Acknowledgements
The list of contributors who participated in this project.

* [GitHub for atom](https://github.atom.io)
* Resources from Christina Penner.
* Michael Ukwenya
* Annas Isa

## FAQs
* The changes I made does not immediately apply
  + The changes made will take a few minutes to update, in the mean time you can try refreshing the page
* where do I see my hosted resume?
  + First select the README source file and click on Settings in your repository, then scroll down to the **GitHub Panel Pages** and click on the link attached to the phrase *"Your site is Published at"*
