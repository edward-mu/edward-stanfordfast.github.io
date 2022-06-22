# Stanford FAST

Website for the Stanford Future Advancers of Science and Technology (FAST) program.

From Edward:
Things I had to do because I've never used Ruby or Jekyll before (2022-06-22, I have a 2020 M1 MacBook Pro):
1. Following http://jekyllrb.com/docs/installation/macos/, installing Ruby and Jekyll

	a. I couldn't get Ruby to install the latest version (3.1.2). So I installed asdf, https://mac.install.guide/ruby/5.html

	b. Installing the latest version of Ruby using asdf, https://mac.install.guide/ruby/6.html. This worked! 

	c. I was getting some additional lines that didn't seem to be doing any harm...

		> chruby: unknown Ruby: ruby-3.1.1

		> chruby: unknown Ruby: ruby-2.6.8p205

	d. So I went ahead and ran `gem install jekyll`.

To get started after cloning the repo:
1. Run `bundle install` to fetch all the necessary gems.
2. Run `bundle exec jekyll serve` to preview the site locally.
