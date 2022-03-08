# Panther X Dashboard #
This is the Dashboard for Panther X Miner, it can support Panther X1 and Panther X2. it was forked from briffy's repository. but It was enhanced by some new features.

* Pull the update package directly through GitHub repo without the need for a separate tar package 
* Support Panther X1 and Panther X2 at the same time
* Support Panther X firmware version display

## Caveats ##

* If you click a button to enable/disable a service, manually refresh a few times until it updates.
* You will likely get a "This site is not secure" banner when you first connect.  This is because I've enabled HTTPS by default with a self-signed certificate.  The reason it is "not secure" is because web browsers prefer certificates to be signed by an authority, not just yourself.  I promise though, HTTPS with a self-signed certificate is way more secure than standard HTTP (don't take my word for it, Google "https vs http") because at least your data is being encrypted this way.  If you care enough, go buy a certificate for a couple of bucks and add it into /etc/ssl/  (you've got root access now).

## Change Log ##

- 0.2.13

1. Fix the issue that dashboard on some machine could not be opened due to certificate exception.
2. Add a password reset prompt, it needs to input at least 6 digits.
3. Fix the issue that it always update failed when click update miner on some panthers.
4. Fix the issue that miner stopped running suddenly on some panthers.
5. Fix the issue that bluetooth cannot be turn on after it running for a long time on some panthers.

## Contribute ##
If you find some issues or problems when you use the dahsboard. you are always welcome to submit the issue here: https://github.com/Panther-X/PantherDashboard/issues
