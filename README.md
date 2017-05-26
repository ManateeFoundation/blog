How to write a blog post
========================
1. Go to the _post folder. 
2. For the first post: edit the file 2014-3-3-Hello-World.md. This file must include the Front Matter [^1] (see below for details).
3. For new posts: Create a new file. The name format must be YY-M-D-the-rest-of-the-title.md
4. Add the Front Matter* to the begining of the file. Use the example below. More identifying Front Matter can be added. See https://jekyllrb.com/docs/frontmatter/
5. Add your blog content under the front matter and save. In a few minutes the blog home page will update with a link to the article.
6. To write a draft: go to the _draft folder.
7. Create a new file. The file name only uses the title, no date. Example: Hello-World.md
8. Drafts will not be published to the site.

For more info on Jekyll, see https://jekyllrb.com/docs/. 

[^1]: Front Matter is the content at the begining of a file that let's Jekyll know it needs to be processed. The Front Matter must be the first thing in the file. It begins and ends with ---. 
Example:

---

layout: post

title: Your title can be anything you want but the layout needs to be post.

---
