# 2021WEB503-Assessment-2


## Moqup
https://app.moqups.com/Ddb2flHpJc/view/page/a2a00afc0 


### Issues
1. Jekyll setup and run: When using ">bundle exec jekyll serve" command Jekyll would not run. 
Fixed after using ">bundle add webrick" and then running ">blundle exec jekll serve".

2. Home page. default jeykll homepage will not work for my requirements. I changed the "home layout" to a "page layout" and put in my details on the markdown file that I wanted featured.

3. I added 2 more pages to the site titled "blog" and "projects". The blog pagee will have posts about journals and articles that I write. The projects page will be a grid of posts with descriptions of the project and a link that is directed to the github of the project. I set these pages to loop through posts and display them on the page. Distinguishing the blog posts and the projeect posts was the issue. I decided to then cateegorize the blogs with "category: "blog"" and the projects with "category: projects"" and then display the posts with a loop through the specific categorize with respect to each page.

4. Publishing to domain.

5. Load time was long. The issue was the size of the images. So I downsized the images using paint.net and made them less than 400px by 400px and the site loaded much quicker.


