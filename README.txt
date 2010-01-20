= MTik -- A Ruby implementation of the MikroTik RouterOS API

The MTik gem implements the MikroTik RouterOS API for connecting to
devices running RouterOS (with the API enabled) over the network.


== Examples

Included in the examples subdirectory are four example ruby scripts
that use the Ruby API implementation:

tikcli.rb::     A command-line-like API interface
tikcommand.rb:: A tool for executing a single API command from
                a unix command-line
tikfetch.rb::   A tool for instructing devices to download files
                from specified URLs (unix command-line tool)
tikjson.rb::    Like 'command.rb' a tool for executing a single
                API command, except the output is formatted  in
                JSON-style


== Download

The latest version of MTik can be found at

* http://www.aarongifford.com/computers/mtik/

Ruby RDoc documentation can be found online at

* http://www.aarongifford.com/computers/mtik/latest/doc/ 

Additional documentation is available at

* http://www.aarongifford.com/computers/mtik/
* http://wiki.mikrotik.com/wiki/API_Ruby_class

For documentation on the MikroTik RouterOS APi, see

* http://wiki.mikrotik.com/wiki/API


== Installation

To install MTik is through its GEM file:

  % [sudo] gem install mtik-3.3.0.gem

== License

This gem and all other scripts and documentation files are licensed
under a BSD-style license.  (See the LICENSE.txt file.)


== Report Bugs

Please report bugs by going to the author's web site and clicking on the
"Contact Me" link in the left-hand menu.  The direct URL is:

* http://www.aarongifford.com/leaveanote.html

Thank you!

-- Aaron D. Gifford
