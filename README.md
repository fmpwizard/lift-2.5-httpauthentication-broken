# Lift 2.5 HTTP basic authentication issue

The path /static/index should be protected by basic authentication but it's not.

The code is directly inspired from http://exploring.liftweb.net/master/index-9.html#sub:HTTP-Authentication

Just change liftVersion to 2.4 in build.sbt and it works again
