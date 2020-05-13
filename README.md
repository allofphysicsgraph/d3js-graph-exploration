
== step 1: run Chrome in an unsecure manner to get around CORS ==
as per
https://stackoverflow.com/a/58865973/1164295

open -na Google\ Chrome --args --disable-web-security --user-data-dir=$HOME/tmp

== step 2: serve files from a local server ==
as per
https://stackoverflow.com/a/17223621

python -m SimpleHTTPServer

== step 3: navigate to page ==

http://localhost:8000/

