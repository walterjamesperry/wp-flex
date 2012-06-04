#WHAT IS IT?
A responsive, foundational Wordpress theme boilerplate for developers submitting to the Wordpress.org theme repository. 

#KID TESTED, DEVELOPER APPROVED:
Tested and Debugged using Wordpress 3.3.2, 'theme-unit-test.xml' and 'wp-config.php'. 

Windows 7 Browser Tests
1. IE      7-9
2. Chrome  18
3. Firefox 12
4. Safari  5
5. Opera   11

Mac Lion 10.7 Browser Tests
1. Firefox 12
2. Chrome  18
3. Safari  5
4. Opera   11

#IT STILL NEEDS YOUR HELP! SOS!
1. In order to submit to the Wordpress theme repo, authors must rename all function calls, variables with the theme name reference to your own new theme-to-be name. Refer here http://codex.wordpress.org/Theme_Review#Theme_Name for rules regarding naming. WP-Flex needs a dynamic means to create a new theme name across our codebase without going through everything line by line. 

For example (using functions.php to illustrate)...
<code>
function wpflex_setup() {
   do_something_great()
}

would be replaced dynamcially with our new name....

function awesomesauce_setup() {
   do_something_great()
}
</code>

#A few suggestions before uploading your theme submission for wordpress' theme repository review
1. Remove all hidden files from the WP-Flex directory (.ds_store, .git, .htaccess) per Theme Check Plugin Review => http://pross.org.uk/theme-check
2. Remove github's 'README' file included for this repository 
3. Rename 'themename-readme.txt' to 'readme.txt' as per Wordpress Codex theme submission requirements 

#UNDER THE HOOD:

1. HTML5 Boilerplate 
   [http://html5boilerplate.com](http://html5boilerplate.com)
2. jQuery
   [http://jquery.com](http://jquery.com)
3. Modernizr
   [http://modernizr.com](http://modernizr.com)

#EVEN MORE!!!

1. themename-readme.txt
   A must have for theme submission. Describes the ins and outs
   to users what is great and what still needs work with your theme.
   (A reccomendation from the Wordpress Codex for theme authors)

2. Detailed PHP comments with URL references for theme submission checks and further customization

3. Required Wordpress CSS classes

4. Comment Thread Styling Classes
   Those tricky comment thread styling classes provided to you by default. No more scanning the DOM or reading more tutorials. It's all there bro! 

5. Standardized CSS Comment Flags 
   css comment flags used for sectioning as reccommended by Wordpress theme submission codex

6. theme-unit/theme-unit-test.xml
   a database for theme testing with multiple users, comment threading, posts and much more

7. WP-Flex Theme Options Boilerplate
   a custom boilerplate starting point to give your users awesome theme and authors theme options

8. Theme Functions Boilerplate
   a creamy base for required functionality of themes and submission via Wordpress.org Theme Repository. http://wordpress.org/extend/themes/upload  

# Some more inspiring and wonderful blank Wordpress theme frameworks to get you going

1. Matt Murtaugh's HTML5 Reset Wordpress Theme
   [http://html5reset.org/#wordpress](http://html5reset.org/#wordpress)

2. Digging Into Wordpress' BLANK Wordpress Theme
   [http://digwp.com/2010/02/blank-wordpress-theme](http://digwp.com/2010/02/blank-wordpress-theme)


Surely you can always visit the Wordpress Codex for more customization and give it a shot yourself 
-thats what I did :)p

[http://codex.wordpress.org](http://codex.wordpress.org)
[http://wordpress.org](http://wordpress.org)