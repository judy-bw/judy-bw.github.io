---
layout: post
title: Why am I taking Electronic Textiles?
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
comments: true
mathjax: true
author: Judy
---

{: .box-success}
This is post to show you why I decided to take Electronic Textiles!

My name is Judy Weintraub and I'm a freshman. I'm a potential **Art History** or **English** major! I do not have much sewing experience, but over the summer I made an embroidery sampler and turned it into a pillow! Here's a photo:

![Crepe](https://beautifuljekyll.com/assets/img/embroidery-summer.jpeg)


When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})

<details markdown="1">
<summary>Click here!</summary>
Here you can see an **expandable** section
</details>
