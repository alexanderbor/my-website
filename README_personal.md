# How to update my website 

First update the website locally hosted in the `szasulja/Sites/my-website`. This will be mostly editing .md files in the "page" folder and adding new pdfs to "assets". 

Next, open the terminal navigate to the location of the website (cd Sites cd my-website).  run `bundle exec jekyll serve` in the Terminal to build the website locally. This should update things in the `_site` folder. 

Then copy-paste things from the `_site` folder into the `szasulja/Sites/compiled-website` folder. These will be .html files and .pdfs. I was hesitant to simply copy-paste the entire `_site` folder, because I was not sure if I had to hack anything in the config. 

Use the steps below to push the `compiled-website` folder on Git. It is at the alexanderbor.github.io project. 

# Solution for embedding CV via Google drive 

https://jamesonzimmer.com/simple-pdf-embed-for-jekyll/ 


- upload pdf to google drive
- make pdf public
- copy embed code
- paste into post
- change inline width and height values to 100%
 

# Push website

1. open Terminal 
2. Navigate to folder "cd Sites" "cd my-website"
3. execute commands below

git add .  
(this adds all new files to a commit)

git status 
(can check if this is indeed the case)

git commit -m "blabla"
(this commits the changes. basically puts a stamp on things)

git push origin master 
(this is gonna sync the commit(s) with online github repo)