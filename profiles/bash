# Is it possible to disable some naughty activities?
# https://gtfobins.github.io/gtfobins/bash/#reverse-shell
# https://gtfobins.github.io/gtfobins/bash/#suid
/{usr/,}bin/bash flags=(complain) {
  # bash is able to do the reverse shell stuff
  # This rule is designed to disable this capability of making reverse shell with bash
  # Mean while, child processes of bash shell are able to connect to internet normally
  deny network,
}
