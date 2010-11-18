# Overview

This is the repo for the content that makes up the ["I Use Riak" page](http://pharkmillups.github.com/i-use-riak).  I Use Riak is place for users to take a few minutes and talk about their applications and projects in which Riak and/or other [Basho software](http://github.com/basho) plays a part. 

## Contributing

Using some Basho software and have 15 minutes to tell the community? Great! Here's how you do it:

1. Fork this repository (See [this page](http://help.github.com/forking/) if you need to read up on forking)
2. Create your "Post" (this will be explained more in depth below)
3. Add your contribution file and any other related files to the repo in the in the "gh-pages" branch of this repo.
4. Send me a Pull Request (See [this page](http://help.github.com/pull-requests/) if you need to read up on Pull Requests)


### Your Contribution ( a.k.a your "Post")

Step two above is "Create your Post." This is where you get to be creative.

Here are some specifics:

**What format does it have to be?** 

The main site for this repo is served up using a feature of GitHub called ["Pages"](http://pages.github.com/). Pages is great for a lot of reasons, not the least of which because it allows for people to write posts in either [Markdown](http://en.wikipedia.org/wiki/Markdown), [Textile](http://en.wikipedia.org/wiki/Textile_(markup_language) or HTML. In other words, write your post in any of these formats and you'll be all set.

**What should my post contain?** 

Whatever you want! Remember, these are your words. 

Check out the [Sample Post](#) for an immediate idea of what a post can contain.

**Naming Your Post** 

The naming convention goes as follows: 

<code>
YEAR-MONTH-DATE-title.MARKUP
</code>

For example, if you authored your post on Dec 1, 2010, were using textile for your markup language, and wanted your post be called "Zhonda" then the file would be named:

<code>
2010-12-01-Zhonda.textile		
</code>

**One Things You Must Do!!**

Every post must start with a YAML header that declares which layout you're going to use. The default layout (as seen in the [Sample Post](#)) is known as, well, 'default.' The YAML header is come configuration information that needs to go at the top of each post. This information is included between triple-dashed lines. 

If you just want to use the default layout, start you file with a triple dash, include the following:

<code>
layout: default
</code>

and then close it off with another triple-dashed line.	

If you want to get super ambitious, you could even create a new layout specifically for your post. Just make sure to reference it appropriately in the YAML header and read up on how [layouts work in Jekyll](https://github.com/mojombo/jekyll/wiki/usage). 

**Can I see how my post looks before I send a pull request?** 

Of course! (We recommend it.)You'll need to have [Jekyll](http://github.com/mojombo/jekyll) installed on your local machine in order to build the site. It just takes a moment, and once you've gotten that taken care of, you can follow the instructions to build the site locally.

**Before you send a pull request**

1. Make sure you've included the YAML Header 
2. Make sure your post goes into the "_posts" sub directory. 
3. If you're including any images, make sure you're using absolute paths

## Additional Resources

Riak Wiki
Basho.com
Download Riak 
Basho's Code on GitHub