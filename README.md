#Piwik Signup Plugin

Created by [Stephan Miller](http://www.stephanmiller.com)

##Installation and Setup
1. Unzip the plugin file.

2. Rename the extracted folder "Signup"

3. Upload the Signup folder to your to the plugins folder of your Piwik installation.

4. Open up your config.ini.php file in the config folder of your Piwik installation and add the following lines to the bottom of the file (without the backticks):
`[Signup] 
enable_captcha = 0`

5. Using your admin account, login to your Piwik installation and visit plugins (installed) in the sidebar on the settings page.

6. Look for the plugin titled "Signup" click the "activate" link it (if it is inactive, otherwise you're done).

For a more visual, yet outdated way to follow steps 2 and 3, please see [http://dev.piwik.org/trac/attachment/ticket/1148/signup.patch](http://dev.piwik.org/trac/attachment/ticket/1148/signup.patch)
