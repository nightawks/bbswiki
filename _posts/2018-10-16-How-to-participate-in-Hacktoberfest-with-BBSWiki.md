---
layout: post
title:  "How to participate in Hacktoberfest with BBSWiki"
author: aman
categories: [ howtoguides ]
image: assets/images/hacktoberfest.png
featured: true
hidden: true
---

## What is Hacktoberfest?

[Hacktoberfest](https://hacktoberfest.digitalocean.com) is a month-long celebration of open source software run by DigitalOcean in partnership with GitHub and Twilio.
To get a shirt, you must make five pull requests (PRs) between October 1–31 in any timezone. PRs can be to any public repo on GitHub, not just the ones highlighted. The PR must contain commits you made yourself.

If you are a newbie in Open Source Domain and looking for an open source project to make your 5 PRs then bingo! You have arrived at the right place.

Follow these steps to start contributing to BBSWiki:

- Fork BBSWiki on your GitHub account.

- Clone BBSWiki on your local computer.
```bash
git clone https://github.com/YOUR_USER_NAME/bbswiki.git
```

- Step over into `bbswiki` directory
```bash
cd bbswiki
```

- Step over into `_posts` directory to create a new post 
```bash
cd _posts
```

- Create a new markdown file to create a new post on `BBSWiki`.
```
touch 2018-10-16-Hello-World.md
```
Note: The first letters of file name should be the date of post and the last letters should be the title of post as shown in above example.

- Copy following template to the newly created file and edit it accordingly.

```markdown
---
layout: post
title:  "How to participate in Hacktoberfest with BBSWiki"
author: YOUR_NAME
categories: [ howtoguides ]
image: assets/images/image.png
---

CONTENT of YOUR POST Written in MARKDOWN Language.
```

Note: If you want to use any cover image[Recommended] in your post, first save it to `assets/image` directory and then reference it in post as shown above. Before writing your name in the post, first add it to `_config.yml` file.

- Add changes to git and commit them
```
git commit -am 'Add New Post'
```

- Push your changes to remote
```
git push origin master
```

- Create a Pull request to BBSWiki repo from your GitHub account.