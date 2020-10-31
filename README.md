# How to host a resume on Github pages

This README will explain how to host your resume on Github and style it using Markdown and Jekyll. I will also explain how these steps are directly correlated to the principles  in Andrew Etter's book _Modern Technical Writing_.

## Prerequisites
Have a resume formatted in Markdown that we can easily import to our Github page. If you do not yet know how to use Markdown, see [More Resources](#More-Resources) and follow the **Markdown tutorial**.

## Step 1 - Create a Github account
First and foremost, you will need to create an account, you can create a free one with [Github](https://github.com/join). 

Additionally, if you are a student, you will be able to sign up using your school email which will grant you more features over the free version. These upgrades include: 
* Private repositories with more than 3 collaborators,
* Privately host 50GB of software packages compared to 500MB, and
* premium support over web or phone

Andrew Etter explains how using a distributed version control system (DVCS) allows for offline work and convurrent work. Yes concurrent work is not needed here since we are the only ones that will change anything. But this will get your foot in the door to what is possible and how the industry operates when working in large groups on software

## Step 2 - Create a repository
Once logged in, you can create a repository in two ways:
1. Go to the main page and click the green **New** button on the top left of the page.
2. Go to your account page and select the **Repositories** tab on the top of the page, then click the green **New** button.

Once we are at the "*Create a new repository*" page. We will need to name our file **_YourName_.github.io** where you would use your username instead of _YourName_. For example, if my account name was AdamA, I would name the repository **AdamA.github.io**.

You can add a description of the repository, in our case we are making a page for our resume. We *MUST* select our repository to be **public** in order for the webpage to work. This will let GitHub know that you are wanting to publicly host your website for others to see.

We can then check the _Add a README file_ button so that Github will make our README for us automatically.

## Step 3 - Create a file called index.md
Put your resume in this file or upload your resume and call it index.md. We call it index because this lets GitHub know to use this specific page when rendering our static website

We use a light wight markup language such as Markdown for a few reasons.
First, we can easily make changes to our resume without having the need to re-convert to a PDF and upload that PDF to have the most up to date version on our webpage.
Another is that Markdown is seemlessly integrated with Github...



## Step 4 - Format webiste using Jekyll
Open your repo, click settings, scroll down to **GitHub Pages** and then click **Change theme**. Once here, you can choose a theme that you like best. Once you click **Select theme**, the theme will automatically be applied to your resume.

Andrew Etter advocated for the use of static sites. He explains how they are fast, simply and secure. When what we are hosting is not very complicated, such as a resume in this case, static sites allow us to quickly create a great looking page that is easy to read and very easy to maintain. Since we are using Markdown for our resume, we can easily make changes to our resume and the next time we load our website, the website automatically rebuilds and displays the most recent version of our resume.

## Step 5 - Check your website
We're almost done. We should now check to see it our website is up and looks how we want it to. All you need to do is type **_Username_.github.io** into your web browser. Now you should be looking at your resume formatted using Markdown and Jekyll.

## (Extra) Step 6 - style using Jekyll

You can further modify your static website using Jekyll by going to the *_config.yml* file.


### More Resources
1. [Markdown tutorial](https://www.markdowntutorial.com/)
2. [Create Github account](https://github.com/join)
3. [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)


## Authors and Acknowledgments



# FAQs
Why is Markdown better than a word processor?
Better because we are able to easily update our resume without having to convert the work file to HTML or PDF and then uppload that. We can easily update our website

| # | Question | Answer |
|---|---|---|
| 1 | Why is Markdown better than a word processor? | Better because we are able to easily update our resume without having to convert the work file to HTML or PDF and then uppload that. We can easily update our website |
| 2 | Why is my resume not showing up? | Check this thing over there... |





