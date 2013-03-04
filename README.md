# Octopress Aside for MailChimp Signup Forms

Use your Octopress blogs to drive readers to sign up for a MailChimp mailing list, with an Aside on every page.

This plugin is quite simple. It consists of a simple modification in the  __\_config.yml__ file and the addition of an aside html in the asides section.

The configuration file must be modified by adding the mailchimp.html aside in the list of default asides and setting four config variables:

* `mailchimp` : set to true
* `mailchimp_list_name` : name of the list
* `mailchimp_list_why` : What's in it for them?
* `mailchimp_embed_action` : a custom URL Mail Chimp provides to you.

To get your Mail Chimp action URL, log in, and pick the list you want to direct people to.

On the list page, click the "For Your Website" drop-down, and pick "Signup Form Embed Code".  In the code sample, copy the URL from `<form action="...">` and paste it into the config option `mailchimp_embed_action`

The __mailchimp.html__ file must be placed in the default asides location:
/.themes/classic/source/\_includes/asides

## INSTALLATION SCRIPT

Not available at the moment. Octopress main repo developers are investigating for a common way to manage plugins. At the moment we wait for specs to be defined before
creating the installer for this simple plugin.

## LINKS

[Octopress 3rd party plugins](https://github.com/imathis/octopress/wiki/3rd-party-plug-ins)
