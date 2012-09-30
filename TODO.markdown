# TODO

* Photos
  * Make them look a little nicer, and automate them
* Layout:
  * Nice typeface, nice spacing
  * ? Single column layout - maximise the reading room
* Post layout
  * Put the post metadata into a nice little box on the right, out of the main flow
  * "Tagged with" metadata, each linked to a tags page for that tag
* Front page:
  * Popular posts box (content to highlight)
  * Recent tweets box
  * Recent comments box
* Change the background color to be off-white, not blue
* Add @gristbrewing to website
* Blog on 4 cider recipes
* Finish up the couple of unfinished beer logs, and put in photos

# Done

* Make `rake deploy` work properly - rsync + SSH keys
* Add prev and next links on the post template
* Pull in all content from the nanoc version
* Figure out permalinks - need to make sure all resources on the old site are still either directly available, or redirected
* Sign up on twitter for @gristbrewing https://twitter.com/GristBrewing
* Push up jekyll grist and re-point server
* Clean up SSH keys between icing and air
* One-off backup of webserver: /home/www, /etc/httpd, database
* Configure automatic backups on webserver, and automatic pulldown of backups to air
* Blog on "Cider Days"

# Other

* Install and use `kramdown` and configure auto code highlighting
* Configure vim to treat liquid code blocks as code blocks - e.g. try adding some clojure to a markdown page...
* Configure vim to handle the yaml front matter
* Move brownsofa.org/blog from WP to Jekyll
* Blog on "How to move from Wordpress to Jekyll"
* Move roseroots DB into AWS PaaS
* Set up load balancer / single IP point of entry, and multiple app servers behind - e.g. m1.micro with Nginx for static blogs, another m1.micro for WP installs
* Blog on "How to get off a VPS, and into a fault-tolerant AWS solution" - basics, ground up.  Perhaps multiple entries.
* Create a dotfiles repo for zsh, vim, ssh, ...
* Create a new .vimrc - clean, with mode switching / rebinding for language
