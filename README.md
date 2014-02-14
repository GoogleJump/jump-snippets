jump-snippets
=============

Simple tool for GoogleJump participants to submit weekly update snippets.


Resources
---------
Some stuff I think might be helpful:

https://developers.google.com/appengine/docs/go/gettingstarted/introduction (go on appengine)
https://developer.github.com/v3/oauth/ (if we want to use github logins)
https://developers.google.com/appengine/docs/go/users/ (if we want to use google logins)
http://developer.github.com/v3/ (if we want to query github for projects or people)


Some sample git setup/interactions
----------------------------------
  git config user.name "Ben Margolin"
  git config user.email "bmargolin@gmail.com"
  git config credential.helper 'cache --timeout=80000'
  git config push.default simple
  nano README.md 
  git commit -am 'added period'
  git push

  git pull

