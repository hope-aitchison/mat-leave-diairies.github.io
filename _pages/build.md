## Blog build

I thought I'd start by sharing how I built this blog. There are many, many ways on how to build a blog, and mine assumes a relatively competent level of experience in development and IaC (infrastructure as code). I am by no means an expert; I'm using this as an opportunity to learn myself and expand my skillset. And no, I didn't set this blog up DURING maternity leave, I did it all before I signed off work.

## The prerequisites
Homebrew
Code editor of choice (I use Visual Studio Code)
A Github account and ssh key already set up

## The hosting set up
### Jekyll
Jekyll renders Markdown or Textile and Liquid templates, and produces a complete, static website ready to be served by Apache HTTP Server, Nginx or another web server.

### Github pages
For information on github pages, see here https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

### Ruby
For information on making sure the correct version of Ruby is installed and you're using the non-system version, see here https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Steps taken
New github repo created using the format blog-name.github.io - this is so that github pages picks up the name of the blog from the title of the repo. You can name the repo whatever you want and then call the source branch directly in github pages. 


Follow the steps here https://jekyllrb.com/docs/installation/macos/ to install supporting dependency software packages

