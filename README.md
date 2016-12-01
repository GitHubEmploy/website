# NUWIT Website
This is the repo for the NU Women in Tech club website. It's hosted on the CCIS servers at [nuwit.ccs.neu.edu](http://nuwit.ccs.neu.edu).


## Getting started
This site is built on a static site generator called [Jekyll](https://jekyllrb.com/). So first, check out Jekyll's [quick start guide](https://jekyllrb.com/docs/quickstart/) and [installation docs](https://jekyllrb.com/docs/installation/).

Once you've installed all the requirements and Jekyll, go ahead and clone this repo onto your computer.

Navigate to the directory and run `bundle install`.

Once everything has successfully installed, you should be good to go!

In your terminal, run `jekyll serve`. This command will start a development server at `localhost:4000` and will watch for local changes automatically.


## Deployment
When you want to push things live, run `jekyll build`. This will generate a fresh build of the project into the `_site` folder.

There are several ways you can push files onto the CCIS server, but the easiest way is probably FTP (File Transfer Protocol). If you haven't used an FTP client before, go ahead and download [Filezilla](https://filezilla-project.org/download.php?type=client) or [Cyberduck](https://cyberduck.io/?l=en).

Under site manager, set up your connection to the CCIS server like so:

![](img/ftp.jpg)

The code for the site lives on the CCIS server at `/net/www/ccs/groups/CISters`. The easiest way to navigate to that directory is by copying and pasting that path into the remote site input like so:

![](img/path.jpg)

When you're in the `CISters` directory, you can drag and drop the files from `_site` into the folder to override the files.


## Caveats
Since the site is hosted on the CCIS server, there are some hoops you may need to jump through in order to push things to the server for the first time. If at any point you find yourself not being able to change things on the server, you probably don't have the right permissions. Go ahead and email [systems@ccs.neu.edu](mailto:systems@ccs.neu.edu) and tell them you're on the NU WIT e-board. They'll be able to give you the right permissions.

Also, for consistency, please use **2 spaces** (NOT tabs, NOT 4 spaces) for indentation!!!
