## Building Blog with GitHub
###  How to create blogs on GitHub account：GitHub Pages, Jekyll, Markdown

#### Let’s get started
#### Step 1 - Create a GitHub account
#### Step 2 - Open the template I built for you

After logging into your GitHub account, open this link and follow the instructions in Step 3:

 ```
https://github.com/chadbaldwin/simple-blog-bootstrap/generate
```

#### Step 3 - Name and create your repository
*If you don’t name your repository correctly, none of this will work
 ```
1. Name your repository like this: {Your GitHub username}.github.io

2. If your GitHub username is “chadbaldwin”, then name it chadbaldwin.github.io

3. Make sure you leave it set to “Public”. If you set it to “Private”, your website will not be published.

4. Now you can click “Create repository from template”.
 ```

#### Step 4 - Customization
we’ll need to make some changes to this file: _config.yml

Change following files:
 ```
 _config.yml
 index.md
 ```

>If you don’t want to provide an email, or any of the social media usernames, you can simply comment them out using #

>you’ll want to edit the index.md file. This is your home page.

>Open up index.md, hit the edit button, and start writing. If you know how to use Markdown, you can use that for formatting, but if you >don’t, that’s okay, don’t worry about it, just write whatever you want, no need to worry about HTML or CSS or anything like that.

>You might be tempted to immediately go to your site to look at the changes, but like I mentioned earlier, you need to wait a minute or two >for GitHub to detect that you made changes, and then it needs to rebuild your site. But eventually, you’ll see the changes.
   
#### Step 5 - Your first blog post
Blog posts are stored in the _posts folder

Blog post files should always be named using this format: yyyy-mm-dd-your-blog-post-name.md

1. Navigate to the _posts folder on GitHub
2. Click Add file > Create new file
3. Name your file 2021-12-18-your-new-blog-post.md
4. Set the title of your blog post by using a markdown header
5. Write this as the first line ## This is my first blog post
6. Add some content…write some random things, whatever you want
7. Throw in a code block (code blocks are created by surrounding your code snippet with three backticks at each end and an optional “language hint”), copy paste this in:Copy(tsql,powershell)
```tsql
tsql
```

```powershell
powershell
```
8.  Important note, if you’re using T-SQL code, make sure to use the tsql tag. This will tell your site that you want to use the SSMS style formatting.
9.  Click the Preview tab so you can see what it looks like so far.（github）

#### Step 6 - pull your blog code to local file

```
cd Blog
git clone git@gitusername:gitusername/programname.git. //becaues I have two git accouts
git pull
git add .
git commit -m "xxxx"
git push
```

Referenced resources：
```
https://chadbaldwin.net/2021/03/14/how-to-build-a-sql-blog.html
https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
```
