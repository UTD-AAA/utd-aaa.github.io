# ✨ Overview <img src="https://i.imgur.com/3qRnjL4.png" alt="drawing" style="float:right;width:42px;height:42px;"/>

This is the official UTD AAA website! It uses [Jekyll] and [RaisinCSS] to make accessibility and updating easier.

### Contents

- [Demo](https://utd-aaa.github.io/)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Resources](#resources)

### FAQ

<details>
<summary>What's Jekyll?</summary>
<br>
Jekyll is a blogging framework used for creating static websites. You create a template directory, which can use different formats, and then it creates a static website from them.
<br>
<br>
</details>

<details>
<summary>What's GitHub pages?</summary>
<br>
A static site hosting service. This is how we’ll be able to host the site for free :)))
<br>
<br>
</details>

<details>
<summary>How is Jekyll related to Ruby?</summary>
<br>
Jekyll is installed as a Ruby gem. Ruby is an object-oriented programming language and gems are basically like libraries (pre-written code, configurations, etc.) with extra data. Bundler is another gem used for tracking, managing, and installing other gems.
<br>
<br>
</details>


<br>
<div id="tech-stack"></div>

# 🥞 Tech Stack

<img src="https://i.imgur.com/51YihOT.png" alt="tsVisual" style="width:500px;"/>


|     |     |     |     |     |
|:---:|:---:|:---:|:---:|:---:|
| Languages | <img src="https://i.imgur.com/znMYAQj.png" alt="drawing" style="width:42px;height:42px;"/><br> Ruby    	| <img src="https://i.imgur.com/7ZpFBVN.png" alt="html" style="width:35px;height:42px;"/> <br> HTML    	| <img src="https://i.imgur.com/XcZjC6l.png" alt="html" style="width:35px;height:42px;"/> <br> CSS       	| <img src="https://i.imgur.com/TyUUxu9.png" alt="html" style="width:35px;height:42px;"/> <br> JavaScript 	|
| Package Managers<br>and Gems 	| <img src="https://i.imgur.com/JBpXlFq.png" alt="html" style="width:42px;height:42px;"/> <br> RubyGems	| <img src="https://i.imgur.com/1rhXneS.png" alt="html" style="width:42px;height:42px;"/> <br> Bundler 	| <img src="https://i.imgur.com/UucVkhZ.png" alt="html" style="width:28px;height:42px;"/> <br> Jekyll  	|     |
| Design Tools | <img src="https://i.imgur.com/IecHDMT.png" alt="html" style="width:42px;height:42px;"/> <br> Whimsical 	| <img src="https://i.imgur.com/87C4exy.png" alt="html" style="width:42px;height:42px;"/><br> Sass   | <img src="https://i.imgur.com/j6hS0Kb.png" alt="html" style="width:47px;height:42px;"/> <br> GitKraken 	|                                                                                                                                	|
|     |     |     |     |     |


<br>
<div id="installation"></div>

# 🔧 Installation

Checkout Jekyll's [Installation guide](https://jekyllrb.com/docs/installation/) for a more in-depth tutorial.
> Note: At the time of making we used Ruby+Devkit 3.1.3-1 (x64)

### Steps
1. Install Ruby with the Devkit
   * [Installing Ruby](https://www.ruby-lang.org/en/documentation/installation/)
   * For Windows:
      * [RubyInstaller for Windows](https://rubyinstaller.org/downloads/)
         * This includes the download of RubyGems, Ruby's package manager.
      * On the last page of the installation wizard, run ```ridk install```
      * If prompted, select ```MSYS2 and MINGW development tool chain```
2. Install the Jekyll Gem and Bundler
   * Open a new command window
   * Run ```gem install jekyll bundler```
        * This installs the Jekyll gem using Bundler, another package manager for Ruby Gems.
   * cd into your project's root and run ```bundle install```
3. Verify Ruby, gem, and Jekyll were installed successfully
   * Run ```ruby -v```
   * Run ```gem -v```
   * Run ```jekyll -v```

### 📌 Notes
   * Running ```bundle exec jekyll serve``` will now build your project on ```http://localhost:4000/``` in your browser.
   * VSCode also has a helpful extension called **Jekyll Run** that provides a button to launch your project.
   * Versions at the time of making:
      * Ruby: ```ruby 3.1.3p185```
      * gem: ```3.3.26```
      * Jekyll: ```jekyll 4.3.1```



<br>
<div id="resources"></div>

# 📚 Resources

### Official Docs

 - [Jekyll documentation](https://jekyllrb.com/docs/)
 - [RaisinCSS documentation](https://github.com/tretapey/raisincss)
 - [Bundler install docs](https://bundler.io/v2.3/man/bundle-install.1.html)

[Jekyll]: https://jekyllrb.com/
[RaisinCSS]: https://github.com/tretapey/raisincss


### Ruby Info/Setup

* [Ruby 101](https://jekyllrb.com/docs/ruby-101/#:~:text=Jekyll%)
* [What are Ruby Gems?](https://medium.com/@morgannegagne/what-is-a-ruby-gem-1eec2684e68)
* [Windows specific Installation](https://stackify.com/install-ruby-on-windows-everything-you-need-to-get-going/)


### Jekyll Info/Setup

* [Jekyll Basics/Installation](https://www.john-cd.com/cheatsheets/Markup_and_Documentation/Jekyll/#:~:text=Jekyll%20Install%20How%2DTo&text=Bundler%20is%20a%20gem%20that,necessary%20dependencies%20each%20gem%20requires.)
* [Jekyll Doc Theme 6.0 - Installation Guide](https://idratherbewriting.com/documentation-theme-jekyll/mydoc_install_jekyll_on_windows.html)
* [Jekyll on Windows 10 - Installation Guide](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/jekyll-install-windows-example-blog-tutorial)
* [In-Depth Website Walkthrough](https://opensource.com/article/21/9/build-website-jekyll)
* [Assets (Sass & CoffeeScript)](https://jekyllrb.com/docs/assets/)
* [Building a Practice Website Video Tutorial ▶️](https://www.youtube.com/watch?v=g6AJ9qPPoyc&ab_channel=SpencerPa)



### Sass

* [Sass Basics](https://sass-lang.com/guide)
* [Sass with Jekyll](https://markdotto.com/2014/09/25/sass-and-jekyll/#install-sass)
* [Adding Sass to Jekyll Video Walkthrough ▶️](https://www.youtube.com/watch?v=qMGw3-cxGhw&ab_channel=ZacharyRNewton)

