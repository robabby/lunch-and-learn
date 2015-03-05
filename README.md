#CSS Lunch & Learn

[View Project Website](http://robabby.github.io/lunch-and-learn/)

This project is focused on educating the basics of CSS.  The project currently includes three pages focused on introducing certain aspects of CSS, and finishes with building a navigation bar.

If you would like to launch this project locally, you will need to have [Ruby & Rails](http://railsinstaller.org) installed, along with the [Jekyll](http://jekyllrb.com) Gem.

After Ruby & Rails are installed in a Command Prompt run the following command to install Jekyll:
	
	gem install jekyll 

Once the installation has finished, navigate to the project directory in a command prompt/terminal and then execute a: 
	
	bundle install 

Once everything has finished installing, you are ready to view the project.

Execute `jekyll serve -w` in the project root to build your project and serve it to http://localhost:4000/lunch-and-learn/

Notice using the `jekyll serve` with the `-w` flag will 'watch' the directory for changes, allowing you to develop your app without having to recompile after your changes.

Happy coding!

---
##### Note 

If you are on Linux or OSX, you do not need the [WDM](http://rubygems.org/gems/wdm) gem.  This is necessary for Windows only.  If you don't need this open the Gemfile at the root of the project and remove line 3.

---
