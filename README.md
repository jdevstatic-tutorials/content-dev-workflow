# My Personal Content Dev Workflow

*`updated 21 April 2022`*

GitHub lets you create digital content
easily as it is using Markdown. That 
really fits for digital content writers,
even for non-code. The most important
is that you can use GitHub without
Git. I don't want to use Git to simplify
this workflow. Don't get me wrong,
Git is a very powerful tool but
for the sake of my workflow simplicity,
I'll not be using it for basic
content creation.

When I'm doing tutorial or lesson 
content, I have my personal 
workflow, so that I am always efficient.
Take note, what I am referring to
is not a software development workflow,
that's a very different one.

The very first rule is that everything
should be online, even the drafts of 
my content, so that I can access it
everywhere. The only downside is that,
if there is no Internet connection, I really 
don't have access to my online content
unless I have an offline backup.

GitHub really is there as my active
site development more than Google Docs
or Microsoft Word. I have covered
this in one of my posts:

<https://github.com/jdevstatic/github-pages-tutorial>

The most important catch is that
you want your content as a plaintext 
format and let it be rendered for
different formats for distribution.
Plus, when you put your content on 
GitHub, it is really efficient
tracking the version of your file
particularly when others
are collaborating with your work.
But even if I'm just alone, it's 
really the best for me.

I tested several workflows of my
own and I want it to be simple as
possible. I tried using GitHub 
Desktop and VS Code or GitHub Gist, etc.,
as additional tools, 
but the workflow would not be that simple.
Don't get me wrong, they are great
technologies but the way I want it
is as simple as possible. So, 
this workflow that I am adhering
too, I am using this whenever
I am creating digital content.

Firstly, I will start creating
a repo here on GitHub and set it
to `private` first. For me, for every
content is a separate repo, no
matter how short the content is.
I will be putting all my 
initial thoughts.
This is still a draft even though
I am using the `main` branch because
this is still private. It is the 
default `README.md` file that is the 
actual page and it should be the only
one for my content. If the
tutorial or lesson is very long,
it can simply have a TOC. GitHub
also added this recently and
by default, it is enabled.

Then, say, I feel that I'm done with
the content, this time, of course, 
I need to proofread, for spelling
and grammar and the structure of the
content itself. I found it out that
the simplest way of doing this
is to use Google Docs. I will 
copy and paste the rendered content
on Google Docs. Don't get me wrong,
I am not using Google Docs
for content creation, 
it is just to check particularly for
spelling. Also, the
structure of the content can be
seen easily there. The only downside
is that sometimes embedded pictures will
not be allowed
on Google Docs but this does
not matter, because the focus
is content structure, spelling
and grammar.

After this, it is now ready. I'll
be making my content public. I
achieved several things here, my
content can be rendered in different
formats like HTML just like the
page generated by GitHub Pages 
or use GitHub Gist
for embedding on another site
or PDF for printing
or downloading, while the repo
on GitHub will still remain the
development site for updates.

Now, when there is an update, this
is the time I use branches 
because the `main` branch is 
always deployable. Even if I'm 
developing alone, this is very 
important. Then, I'll push the changes
in the `main` function when it's
ready.

So, there you have it. To summarize:
1. Create a private repo. Consider it
as a draft. And then, the final step
is to proofread using Google Docs
for spelling and grammar.

2. Once all checks are done, make it
public. This is already the final version.
This can be rendered in several formats
for distribution.

3. When there is an update, use 
branches because the `main` branch
is always the deployable branch.
Then just merge the branch into
main by pull request when
it's ready.
