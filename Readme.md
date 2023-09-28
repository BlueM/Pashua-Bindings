About this repository
======================

This repository does not contain any code itself, but merely serves for listing Pashua bindings in various languages and for providing information on writing bindings and having them listed on this page.

[Pashua repository on GitHub](https://github.com/BlueM/Pashua)


Bindings
============

* [AppleScript](https://github.com/BlueM/Pashua-Binding-AppleScript)
* [AppleScript](https://github.com/doekman/ASPashua) Alternative binding, as Script Library
* [Bash](https://github.com/BlueM/Pashua-Binding-Bash)
* [JavaScript for Automation (JXA)](https://github.com/RobTrew/Pashua-Binding-JXA)
* [.NET](https://github.com/davidaramant/PashuaNetBindings)
* [Perl](https://github.com/BlueM/Pashua-Binding-Perl)
* [PHP](https://github.com/BlueM/Pashua-Binding-PHP)
* [Python](https://github.com/BlueM/Pashua-Binding-Python)
* [Rebol](https://github.com/ldci/Pashua)
* [Rexx](https://github.com/BlueM/Pashua-Binding-Rexx)
* [Ruby](https://github.com/BlueM/Pashua-Binding-Ruby)
* [Tcl](https://github.com/BlueM/Pashua-Binding-Tcl)

Deprecated bindings
---------
* [Groovy](https://github.com/BlueM/Pashua-Binding-Groovy) The Groovy binding was distributed of part of Pashua versions 0.9.4.5 through 0.9.5.1. As of August 2014, it is deprecated and no longer maintained.


Contributing bindings to this list
===================================
It is pretty easy to write a binding for using Pashua. And as basically you can use Pashua from any language that is able to write a file or write to a Unix pipe, call an application with command line arguments, manipulate strings and declare variables dynamically or handle associative arrays, Pashua is probably usable from most programming languages that run on macOS.

If you have written code in a language not listed above (example: JavaScript/Node.js) and would like to have it listed here, please contact me with the details (especially the URL or repository) where your code can be found.

Equally, if you have written code in one of above languages that follows a different approach (for instance: you have implemented a binding for PHP which offers a clean OOP API instead of the generic, configuration-based approach in the PHP code liste above), please don’t hesitate to [contact me](http://www.bluem.net/en/contact/) if you want the code to show up on this page.

Your binding should follow these rules:
* It should contain information on the license (PD, MIT, …)
* It should contain information on Pashua version compatibility, i.e.: minimum and/or maximum supported/tested version.
* It should contain information on compatibility with the programming language. Examples would be Python 2 vs. Python 3 or PHP < 5.3 vs. PHP >= 5.3. Also, if OS X includes the programming language, you should include information on whether the binding runs with the default language version shipped with OS X.
* If there is a generally accepted guideline for code-style in the language, the code should conform to it. Example: Python code should comply with PEP8, and PHP code should follow PSR-1.
* You should provide at least one example
* The Pashua application should be searched at least in these filesystem locations: The directory containing the binding code, `.` (the current working directory), `/Applications` and `~/Applications`
* If possible, errors should be written to STDERR and the exit code should be non-zero

Please note that at the moment, not all of the bindings listed above necessarily follow these rules.
