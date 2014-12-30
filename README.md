Getting Started
==
First, install Ruby if you haven't already.
Windows users: we recommend using [Ruby Installer](http://rubyinstaller.org/).
OS X users: we recommend installing [HomeBrew](http://brew.sh/) to install Ruby.
```sh
brew install ruby
```

Now fork the [techlahoma_lander](https://github.com/techlahoma/techlahoma_lander) project into https:// github.com/_username_/techlahoma_lander

Next, clone your fork and install rubies
```sh
> git clone https://github.com/username/techlahoma_lander.git
> cd techlahoma_lander
techlahoma_lander> bundle install
```

Now you can run the site locally with Middleman.
```sh
techlahoma_lander> middleman server
```

You can view the site at http://localhost:4567.

Make your changes, commit and push to your repo.
```sh
techlahoma_lander> git commit -am "my awesome changes"
techlahoma_lander> git push
```

Now open a **[Pull Request](https://github.com/techlahoma/techlahoma_lander/pulls)**, to get your changes merged into the main repo.

Build and Deploy with Middleman
==
Building and deploying run against the main repo, so you'll need to clone the main site.
```sh
> git clone https://github.com/techlahoma/techlahoma_lander.git
> cd techlahoma_lander
techlahoma_lander> bundle install
```
Now, let Middleman do it's magic.

Build it
===
```sh
techlahoma_lander> middleman build
```

Deploy it
===
The deployment will push to the `gh-pages` branch of the **techlahoma_lander** project.
```sh
techlahoma_lander> middleman deploy
```

That's it! :-)

If you have any problems, please reach out to us on Github in issues and comments or on twitter [@techlahoma](twitter.com/techlahoma).
