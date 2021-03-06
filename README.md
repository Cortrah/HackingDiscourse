# Discourse Notes

Half owners manual and half reference guide for hacking the Discourse open source forum software.

# Why Discourse?

I've been developing client side software for twenty years now. I've tried a number of times to delve into the server side, but there are a lot of different concerns on the server side than what I'm used to. And I've been pretty disappointed with the quality of instructional materials on how to write server side software. Most material tends to be tutorials that regurgitate toy examples that focus on basic language syntax that would have been easy to figure out anyway. While they don't deal with real api design, testing, security, database issues, caching, hosting or maintenance in any useful way. Faced with that continual disappointment, I decided to go back to the basics and find some source code to read.

Discourse is a real world, well engineered, 100% open source project that attempts to address some high level problems with online discussion. They have many tests, a postgres database and both client and server software that is written with modern practices. 

By hacking Discourse it means that you also have good examples of

* A Ruby on Rails Api
* An Ember front end Application
* A Postgres database
* A Redis cache and transient data store
* Vagrant 
* Docker 
* Sidekiq

**As a product**

As a product discourse is a good piece of modern software that one can use to host small communities of a few hundred users with a 20 dollar a month Digital Ocean account. Setup is easy, many customization options are included in the admin panel and as it is 100% (GNU GPL) open source, customization is essentially unbounded. The only other forum software that I know of which works well on mobile devices is NodeBB and while that looks promising as well, the Discourse developers have put a lot of thought into the social and admin aspects of their design as well as the technical. Discourse is certainly more mature and runs a ton of active communities. In the end I'm really using it as an example of engineering rather than purely as a product, but do hope to learn the strengths and weaknesses of it as a product as a part of this process. I am just glad that there is more than one open source group adresssing this market and that you can host your own community rather than relying on Facebook or some other Heather* outside of your control.

I just need a place to organize the information that I gather, even if it's just cutting and pasting from other resources. I'm also going to try and get the local Ruby Brigade users group to work with me as I go through this process in hopes that we can learn more from one another.

I also like how gitbook let's me save my books for my kindle device so that I can read while walking the dog.

Finally even just the process of curating, selecting and editing content is a good learning process that helps you cull down the noise and put together the stuff that you need to remember.

# Summary

* [Developer Setup](developer_setup.md)
   * [Mail Catcher](mail_catcher.md)
   * [Quick Start with Vagrant](quick_start_with_vagrant.md)
   * [Custom Vagrant Setup](custom_vagrant_setup.md)
   * [Native OSX Setup from Scratch](native_osx_setup_from_scratch.md)
* [Running Locally](running_locally.md)
* [Admin Quick Start](admin_quick_start.md)
* [Plug In Development](plug_in_development.md)
   * [Part One Getting Started](part_one_getting_started.md)
   * [Part Two Plugin Outlets](part_two_plugin_outlets.md)
   * [Part Three Custom Settings](part_three_custom_settings.md)
   * [Part Four Git](part_four_git.md)
   * [Part Five Admin Interfaces](part_five_admin_interfaces.md)
   * [Part Six Aceptance Tests](part_six_aceptance_tests.md)
* [Security Notes](security.md)
* [Testing Notes](testing.md)


 *(Where Facebook, Google and Apple are Heather, Heather and Heather of the movie "Heathers")




