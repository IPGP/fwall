# fwall

Script to login/logout from a Stormshield firewall

Like the one at IPGP :wink:

## Installation

You will need `curl` (installed by default on macOS, instructions for Ubuntu
[here]) and [Java Web Start].

[here]: https://www.cyberciti.biz/faq/how-to-install-curl-command-on-a-ubuntu-linux/
[Java Web Start]: https://www.java.com/en/download/faq/java_webstart.xml

Recommended: add the `fwall` directory to your `$PATH`.

## Usage

To login, type in your terminal:

```
$ fwall login
```

The script will ask for username and password and propose to store your
login credentials on macOS or Linux keychain (if available) or in a
read-protected file.
A Java Web Start window will open.

To logout, first close the Java Web Start window, then type:

```
$ fwall logout
```
