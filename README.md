# Stanford FAST

Website for the Stanford Future Advancers of Science and Technology (FAST) program.

From Edward (2022-06-22, I have a 2020 M1 MacBook Pro). Things I had to do because I've never used Ruby or Jekyll before:
1. Following http://jekyllrb.com/docs/installation/macos/, installing Ruby and Jekyll (prerequisities here: http://jekyllrb.com/docs/)
	a. I couldn't get Ruby to install the latest version (3.1.2). So I installed asdf, https://mac.install.guide/ruby/5.html
	b. Installing the latest version of Ruby using asdf, https://mac.install.guide/ruby/6.html. This worked! 
	c. I was getting some additional lines that didn't seem to be doing any harm...
		> chruby: unknown Ruby: ruby-3.1.1
		> chruby: unknown Ruby: ruby-2.6.8p205
	d. So I went ahead and ran `gem install jekyll`.
	e. Note: https://www.markdownguide.org/basic-syntax/#lists-1 is helpful for formatting Markdown, which I've also never done before!
2. Following the rest of the guide here: http://jekyllrb.com/docs/
	a. Ran `gem install jekyll bundler`.
3. How to cd into the folder where I'm storing the website files:
	a. `cd 'OneDrive - Stanford'/'FAST'/'FAST Website'/'stanfordfast.github.io'`


To get started after cloning the repo:
1. Run `bundle install` to fetch all the necessary gems.
2. Run `bundle exec jekyll serve` to preview the site locally.
