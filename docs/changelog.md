## Project Olly Changelog

# 2019.6.1
* Added object based tournament sorting
* Updated framework to support the latest version (Django 2.2)
* Move SocialInfo out of StaticInfo to improve speed performance
* Added SocialInfo middleware
* Streamline adding credits to the store via the staff panel
* Merge edit user type and modify user forms into one
* Added Delete News Posts in staff panel
* Fixed FA Map icon not showing up in staff navbar
* Fixed gray bar in staff panel (breadcrumbs broke)
* Show number of open tickets on staff index
* Implemented fix for timezones and tournament registration
* Added latest build of Wagers (still in active development)
* Added Object Based Map Pools

# 2019.3.2
* Object based support ticket categories #525
* (Custom) Mailchimp integration #518
* Fixed button styling with resetting passwords #495

# 2019.3.1
* Implemented country field for teams #469
* Fixed various styling issues on a per client basis.

# 2019.2.2
* Updated framework to 2.1 #457
* Updated routing syntax (backend only) #355
* Social media information is now dynamic and can be changed in the staff panel #491
* Staff panel can search credit transfers by userid. #28
* Staff panel can now assign a user to a support ticket #220
* Fixed backend error with the staff panel if there were 0 teams in the database #479
* Send an email to users if a match becomes disputed #308
* Allow users to optionally back out of important site messages #408
* Fixed join tournament page not having a title #498
* Verify/unverify a user redirects to staff index rather than user list #493
* Users can search for each other by xbl or psn #419

# 2019.2.1
* Swap news post urls to use slugs instead of day, month and year.#475
* Update tournament bracket templates - fixes some styling issues #486
* Fixed tournament forwarding algorithm #477
* Invite only tournaments - manually add teams to tournaments #314
* Match forwarding properly lines up with matches of the previous round #470
* Staff panel match detail shows match reports #182
