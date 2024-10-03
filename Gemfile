# frozen_string_literal: true
# A gem is a package of Ruby code that adds functionality to your project. This file lists all the gems your project needs.

# This line makes all string literals in the file unchangeable, which can improve performance and save memory.

source "https://rubygems.org"
# This line tells Ruby where to download the gems that our project needs. RubyGems.org is the main website for Ruby gems.

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }
# This line sets up a shortcut for downloading gems directly from GitHub, which is a website where developers share their code.

gem "jekyll", "~> 4.3"
# This line adds the Jekyll gem to our project. Jekyll is a tool that helps create static websites. We're using version 4.3 or a similar, compatible version.

gem "jekyll-last-modified-at", git: "https://github.com/maximevaillancourt/jekyll-last-modified-at", branch: "master"
# This line adds a special Jekyll plugin (an extra feature) that can track when files were last changed. It's getting this plugin directly from a specific place on GitHub.

gem "webrick", "~> 1.8"
# This line adds the WebRick gem, which helps run a local web server (a program that lets you view your website on your own computer). We're using version 1.8 or a similar, compatible version.

gem "nokogiri"
# This line adds the Nokogiri gem, which helps read and process HTML and XML files (types of files used to create web pages). We're not specifying a particular version, so it will use the latest available.