<p align="center"><a href="http://www.websvn.info/" target="_blank"><img src="http://www.websvn.info/img/logo-websvn.png"></a></p>
<p align="center">Online subversion repository browser.</p>

## Why WebSVN?

WebSVN offers a view onto your subversion repositories that's been designed to reflect the Subversion methodology. You can view the log of any file or directory and see a list of all the files changed, added or deleted in any given revision. You can also view the differences between two versions of a file so as to see exactly what was changed in a particular revision.<br />
More info on http://www.websvn.info/.

## Features

* Easy-to-use interface, simple to install / configure
* Supports multiple repositories, local or remote
* Optional path-based restriction of privileges
* Colourisation of file listings; MIME type support
* Blame (annotation) view of file authorship
* Comparing revisions of files / directories
* Revision and log message browsing / searching
* RSS feed support for watching any resource
* Download of files and folders
* Customisable templating system
* Multiple languages and on-demand switching

Since it's written using PHP, WebSVN is also very portable and easy to install.

## Requirements

WebSVN uses a command-line SVN client for accessing repositories. Depending on the WebSVN version used, different versions of SVN are required:

| WebSVN version | SVN version                               |
| -------------- | ----------------------------------------- |
|          2.3.x | 1.4 or higher (usage of "@PEG"-revision)  |
|          2.2.x | 1.4 or higher (usage of "@PEG"-revision)  |
|          2.1.0 | 1.2 or higher (usage of "svn list --xml") |
|         <= 2.0 | any (?)                                   |

WebSVN currently runs under both PHP 4 and PHP 5.

## See it in action

A demo of the *latest official release* of WebSVN can be found at http://demo.websvn.info<br />
A demo of the *latest trunk revision* of WebSVN can be found at http://trunk.websvn.info

Note: These demos work off a local mirror of the WebSVN repository which is not synchronized automatically.

## Contribute

You can help us in the development of WebSVN by finding bugs, sending patches and submit issues and translations.<br />
Also feature requests and feedback is always welcome.<br />

* [WebSVN mailinglists and archives](http://websvn.tigris.org/servlets/ProjectMailingListList)
* [WebSVN issue tracker](http://websvn.tigris.org/servlets/ProjectIssues)
* [Github issue tracker](https://github.com/crazy-max/websvn/issues)

## Links

If you know setup tutorials, links to themes etc please contact us.

* [Tigris.org project page](http://websvn.tigris.org/)
* [Setting up subversion and websvn on debian](http://www.howtoforge.com/debian_subversion_websvn)
* [Analysis of WebSVN source on Ohloh.net](https://www.ohloh.net/p/websvn)

## Developers

WebSVN has been originally developed by Tim Armes.<br />
It is now maintained by @dirk-thomas and @quinntaylor.

## License

WebSVN is released under the [GNU General Public License](http://www.fsf.org/licensing/licenses/gpl.html).