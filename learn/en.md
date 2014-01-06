# Passwords

## For Developers

+ Never store the password itself.
+ Force users to choose a longer password, not a difficult to remember password -> [xkcd.com/936/](http://xkcd.com/936/)
+ Ask your users to change their password according to importance of their account / your site on a yearly/quarterly/monthly basis.
+ Use HTTPS at least for Login/Signup/Reset and related pages.
+ Never send plain password of users to their email.
+ Double check ```chmod``` of your files and folders.
+ Your partner(designer) will use the same validation as you, but with javascript. You should run the server-side validation, too. You [can't trust](https://en.wikipedia.org/wiki/User_agent#User_agent_spoofing) user-agent.
+ Use [strong](#for-everybody) passwords for accessing the developping land! After all you are an important person.

## For Designers

+ Although there is a backend for validation, Javascript could do it's job and disable submit button until there is valid password. But don't worry. Backend would do it's job anyway.
+ Make the validation [inline](http://www.goodui.org/index_b.html#33).

## For Everybody

Since Security is an important thing, I've added some recomendation for you about security, too.
+ A great password is:
    + long -> [xkcd.com/936/](http://xkcd.com/936/)
    + simple to remember -> Explanation 
    + something that nobody can guess it. ->
    + different than other important passwords --> some site/forums force you to join for a little information! use same password for all of those sites. But use a STRONG password for your Banking Account and important files.
+ Make sure there is no software/hardware keylogger on your system.
+ Make sure you are connected to a [safe Internet](https://en.wikipedia.org/wiki/Firesheep). Read [this](http://readwrite.com/2010/10/25/at_a_cafe_i_can_hack_your_facebook_twitterwith_a_f), too
+ Since handheld devices(Tablet, Smart Phones, etc.) show each character when you type a password and then make a ```*```, be sure that nobody's watching you when you type your password.