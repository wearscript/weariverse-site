# Weariverse Builder

This tool builds the user facing Weariverse

##Data

You need the latest copy of the script YAML in `data/shared.yml` to build the site.

##Running locally

The site is powered via Middleman and is the standard configuration, with deployment on gh-pages.

0. Dependencies (Ubuntu 13.04): sudo apt-get install rake bundler ruby1.9.1-dev nodejs
1. Install gems needed with `bundle install` (may require sudo depending on gem path permissions)
2. Run the local development server `middleman server`
3. Verify your changes
4. Deploy to gh-pages with `rake publish`
