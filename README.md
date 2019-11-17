# ghost-nginx
A sample docker compose project to get ghost and nginx up and running. So you can expose the ghost instance with standard http port 80.

###Notes
This **docker-compose.yml** file will get the "nginx & ghost" combination up and running.
The domain name used is

**blog-test.froestl.com**

You can replace this domain name by any other you would like by "search & relpace" within the config files in this project.
In addition you need to make a dns entry for that domain pointing on the host you've your running the compose file

Right now only http is configured. For https you need suited certificates and some more config work to be done.
`
####Windows

make the chosen domain name entry in

C:\Windows\System32\drivers\etc\hosts

e.g.:

127.0.0.1 blog-test.froestl.com

_you might need to run your editor in admin mode_

####Linux

make the chosen domain name entry in

/etc/hosts

e.g.:

127.0.0.1 blog-test.froestl.com

###How to run
- change to this directory
- docker-compose-up
- your browser should get the content with http://test-blog.froestl.com
- content edit can be docne with http://test-blog.froestl.com/ghost



