# How to host an Online Resume
## Purpose:
1. This **README** will help you host your resume on github page step by step.
2. Principles, from [Modern Technical Writing: An Introduction to Software Documentation](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS), are applied to this **README**.
***
## Table of Contents:
  >1. [Prerequisites](#Prerequisites)
  >2. [Instructions](#Instructions)
  >3. [More resources](#More-resources)
  >4. [Authors and Acknoledgments](#Authors-and-Acknowledgments)
  >5. [FAQs](#FAQs)
***
## Prerequisites
  >1. Github account
  >2. A resume formatted in [Markdown](https://www.markdowntutorial.com/)
***
## Instructions:
**1. Sign in your account on github page:**
  >1. Go to main page of [github](https://github.com/)
  >2. Click **Sign in** button which is located on right-up corner of the page.
  >3. Type your registered Email Adress and password, then click **Sign in** button
  ![signin](/assets/signin.gif)

Today is a good day

**2. Creat a new repository:**
  >1. After logining in the account, website will automatically directs to main page.
  >2. Click **New** Button which is green button on left panel.
  >3. Type your repository name. Format is "your_won_name.github.io"
  >4. Click **Public** check box to select if necessary.
  >5. Click **Add a README file** check box to select it.
  >6. Click **Create repository** button which is located at bottom of the page.
  ![creatre](/assets/creatrep.gif)
  
**3. Set up a theme for your resume:**
  >1. Click **Setting** to access setting menu
  >2. Scroll down until you see **Github page** menu
  >3. Click **Choose a theme** button to select a theme you prefer, then click **Select theme** button
  >4. Scroll down until you see **Commit changes** button, click it.
  >5. A new branch called "**gh-pages**" is created and you are in this branch now.
  ![settheme](/assets/settheme.gif)

**4. Upload your resume:**
  >1. Click **pen icon** which is located on right-up area. ![uploade](/assets/pen.png)
  >2. Delete all contents in the file, then paste your resume
  >3. Scroll down until you see **Commit changes** button, click it.
  >4. If you want to edit your resume on github page, please edit it in **ph-pages** branch.
  ![upload](/assets/upload.gif)

**5. Check your resume online:**
  >1. Wait for some minutes. Servers need time to set up your online resume.
  >2. Click **Setting** to access setting menu
  >3. Scroll down until you see **github page**
  >4. There is a message:"**Your site is published at https://cbm6.github.io/chenboma.github.io/**"
  >5. Click the link or directly type the address in the address bar. Format is:"Your_account_name.github.io/your_repository_name"
  ![result](/assets/result.gif)
***
## More resources:
- [Markdown tutorial](https://www.markdowntutorial.com/)
- [Modern Technical Writing by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- [Set up Markdown Editor](https://www.portent.com/blog/copywriting/content-strategy/atom-markdown.htm)
***
## Authors and Acknowledgments:
- Andrew Ette.
## FAQs
  > 1.Why is Markdown better than a word processor?
  >- First, operations of **word processors** are _more_ complicated. It requires people more time to write an documentation. I will take **Microsoft Word** as an example, because **Microsoft Word** is the most famous word processor. For example, if you wanted to change a heading's size. In **Microsoft Word**, you need to select that heading and choose a proper font size and font style for it. In **Markdown**, you just change number of "#" before the heading. Secondly, independency. People could edit **Markdown** file on many platforms(text editor, atom, Xcode, etc). **Microsoft Word file** can only be edited on **Microsoft Word file**. Thirdly, **Markdown file** can directly turn into **html file** and be hosted online. So, **Markdown** is better than **a word processor**.
  
  >2. Why is my resume not showing up?
  >- It is mendtioned in **instruction** section. Server needs several minutes to apply theme to your resume and host your resume online.
  >- If your resume was still not showing up, check your internet.
  >- If you followed the instruction and your internet is fine, there might be a problem on server side. You can check github status over [here](https://www.githubstatus.com/).
