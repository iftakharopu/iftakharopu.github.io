# Beautiful Jekyll
*Beautiful Jekyll** is a ready-to-use template to help you create a beautiful website quickly. Perfect for personal sites, blogs, or simple project websites.  [Check out a demo](https://beautifuljekyll.com) of what you'll get after just two minutes.  You can also look at [my personal website](https://deanattali.com) to see it in use, or see examples of websites other people created using this theme [below](#showcased-users-success-stories).

# FAQ and support

If you need any help, I suggest heading over to the [Jekyll support forum](https://talk.jekyllrb.com/).

Beautiful Jekyll is actively used by thousands of people with wildly varying degrees of competency, so it's impossible to answer all the questions that may arise. Below are answers to a few very common questions. Most questions that I get asked are not directly related to this theme, and instead are more general questions about Jekyll or web development. Many such questions can be answered by reading the [Jekyll documentation](https://jekyllrb.com/) or with Google.

### What if I don't want the website to be `https://<yourusername>.github.io`?

Every GitHub user can have one repository (repository = project) named `<yourusername>.github.io` and the website for that repository will be `https://<yourusername>.github.io`. 

If you want your project to be named something else, for example `MyAwesomeProject`, that's no problem! All you have to do is go to _Settings_ at the top right corner of the page, and rename your repository to `MyAwesomeProject` (**remember to click on the _Rename_ button to confirm!**). Then you need to scroll down to the _GitHub Pages_ section and choose "master branch" as the source (not "master branch /docs folder"!).

Now your website will be at `https://<yourusername>.github.io\MyAwesomeProject`.

### How do I change the number of posts per page OR the colour of the navigation bar OR the image in the navigation bar OR ...?

Beautiful Jekyll is built to be very customizable, and as such, many questions about "how do I change ..." can be answered by looking at the `_config.yml` file. The configuration file has many adjustable parameters to customize your site.

### How do I add a favicon to my site?

Easy! Just place a valid `favicon.ico` in the root directory of your project. And then wait! It can take a while to update.

### How do I move the blog to another page instead of having it on the home page?

The default style of Beautiful Jekyll is to feature the blog feed on the front page. But for many sites that's not the ideal structure, and you may want to have a separate dedicated page for the blog posts. To have the blog hosted on a different URL (for example at `<mysite.com>/blog`), copy the `index.html` file into a folder with the same name as the desired page (for example, to `blog/index.html`), and in the `_config.yml` file you need to add a parameter `paginate_path: "/<page name>/page:num/"` (for example `paginate_path: "/blog/page:num/"`).

### What size do you recommend using for the `cover-img` photos?

Unfortunately, this is a no-answer! There isn't a one-size-fits-all solution to this, because every person will view your site on a different browser with different dimensions. Some browsers will have very wide aspect ratio, some will be narrower, some will be vertical (such as phones), different phones have different screens, etc. The image will always be centered, so the only tip I can give is that you should make sure the important part of the image is in the middle so that it'll always show. Other than that, every browser will show a different clipping of the image.

### How do I use MathJax equations in my posts?

MathJax can be easily integrated into your website with a one-line addition. You can see [this discussion](https://github.com/daattali/beautiful-jekyll/issues/195) for more information.

# Contributions

Thank you to [all past contributors](https://github.com/daattali/beautiful-jekyll/graphs/contributors). If you find any problems or would like to contribute in any way, feel free to create a pull request/open an issue/send me a message.  Any comments are welcome!

You can also contribute by becoming an [official sponsor](https://github.com/sponsors/daattali) to help keep beautiful-jekyll well-maintained.

