---
layout: post
title: Installing Jekyll SEO Tag
tag: 
   - tech
published: true
---
<!--break-->

'Add the following to your site's Gemfile:
gem 'jekyll-seo-tag'
Add the following to your site's _config.yml:
plugins:
  - jekyll-seo-tag
Add the following right before </head> in your site's template(s):
{% seo %}'
