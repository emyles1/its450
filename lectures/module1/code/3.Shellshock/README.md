# Shellshock Attack

There is no source code in this chapter?! Just kidding :smirk:

## 1. code list
* [phpinfo.php](.phpinfo.php): show all PHP configuration information
* [env.php](./env.php): pass browser input to server environment variables
* [vul.c](./vul.c): program vulnerable to shell-shock attack
* [variable.c](./variable.c): the buggy code entails shell-shock vulnerability
* [phpinfo.php](./phpinfo.php): show all configuration information of the web server
* [myprog2.cig](../../../../labs/lab04/code/myprog2.cgi): a *hello world* cgi program in bash script
* [myprog3.cig](../../../../labs/lab04/code/myprog3.cgi): a *vulnerable* cgi program in bash script

## 2. References
* Command-line HTTP clients
  * [HTTPie](https://httpie.org/)
  * [HTTP Prompt](http://http-prompt.com/)
* Client URL
  * [cURL](https://en.wikipedia.org/wiki/CURL)
    * [curl](https://curl.haxx.se/)
    * [source code](https://github.com/curl/curl)
    * [https://curl.haxx.se/docs/comparison-table.html](https://curl.haxx.se/docs/comparison-table.html)
  * [wget](http://www.gnu.org/software/wget/)
* [SEED Shellshock Attack Lab](https://seedsecuritylabs.org/Labs_16.04/Software/Shellshock/)
* [Shellshock (software bug)](https://en.wikipedia.org/wiki/Shellshock_(software_bug))
  * [CVE-2014-6271](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6271)
  * [Alert (TA14-268A)](https://us-cert.cisa.gov/ncas/alerts/TA14-268A)
  * [CVE-2014-6271 Detail](https://nvd.nist.gov/vuln/detail/CVE-2014-6271)
* [netcat](https://en.wikipedia.org/wiki/Netcat)
* [How To Customize Bash Prompt in Linux](https://phoenixnap.com/kb/change-bash-prompt-linux)