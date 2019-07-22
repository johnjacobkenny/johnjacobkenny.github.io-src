Title: A pelican powered blog
Date: 22-07-2019
Tags: pelican

I have been cozying up to the idea of creating a static blog + portfolio website for sometime. I finally got around to creating it. The styling isn't how I want it, but this should be a good place to start and get used to the workflow.

I got stuck about the implementation of keeping the code and the output separate. After much searching I found that git submodules would help to keep things separated.

So I setup a main `src` repo for the source code and then setup the main `github.io` repo for the published content. The latter was kept as a submodule in the former.