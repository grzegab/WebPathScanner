# Description
This is a path scanner for websites. Goal is to find urls in JS that are
not protected. For example there might be a path where important settings 
are changed and it's based only on user id (which can be discovered from 
e.g. profile page)

##First version
First version will be simple and won't use cookies. 
It will only scan website for all paths

##Second version
It will use login (accept external cookies)

##Third version
It will accept cookies and find other pages in same domain to be scanned

##Fourth version
It will be more interactive, maybe a web interface will be added

##Fifth version
Check JS variables for additional settings