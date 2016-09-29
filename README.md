
# stamp-qs.awk

  A small awk script to add sha1 hashes to the querystring of your js and css
  files. This is useful if you have a caching web server, so that you can force
  refresh files that have changed on deploy.

## Usage

    $ gawk -v root=public -f stamp-qs.awk < example.html

Where root is the root directory to look for the files in
