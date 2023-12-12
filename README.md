# this repo no longer support anymore

<h1 align="center"> WEBIN ( Website Base Exploiting Tools )</h1>

<p align="center">
<img src="https://img.shields.io/badge/Version-1.0-purple?style=for-the-badge">
<img src="https://img.shields.io/github/license/1337r0j4n/webin?style=for-the-badge">
<img src="https://img.shields.io/github/stars/1337r0j4n/webin?style=for-the-badge">
<img src="https://img.shields.io/github/forks/1337r0j4n/webin?color=orange&style=for-the-badge">
<img src="https://img.shields.io/github/issues/1337r0j4n/webin?color=pink&style=for-the-badge">
</p>

<p align="center">
<img src="https://img.shields.io/badge/Open%20Source-Yes-darkcyan?style=for-the-badge">
<img src="https://img.shields.io/badge/Written%20In-Bash-darkblue?style=for-the-badge">
<img src="https://img.shields.io/badge/author%20-1337r0j4n-brown?style=for-the-badge">
<img src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2F1337r0j4n%2Fwebin&countColor=%23263759">
</p>

## Avaliable Tools
- **Admin Panel Finder**
  - Default Wordlist ( 12661 Lines )
  - Custom Wordlist Can Be Useed
- **Basice Information Scanner**
  - HTML Title
  - IP Address
  - HTTP Server
  - Country
  - CMS
  - robots.txt Check
  - phpmyadmin Check
  - Reverse IP Domains Check
  - Subdomains Enumerations
  - Extract Links
     - Website
     - Images ( JPEG, PNG, GIF, WebP, BMP, SVG,... ) 
     - Others ( PHP, HTML, CSS, JS,... )
- **Bulk Domains To IP**
- **GOOGLE Dorking**
- **Mass CMS Detector**
  - Support CMS 10+ ```( WordPres, Joomla, OpenCart, Drupal, Magento, PrestaShop, Concrete5, Weebly, DokuWiki, Jekeyll )```
- **Mass HTTP Status Code Checker**
- **Reflected XSS BruteForce**
  - Default Wordlist ( 2248 Lines )
  - ~~Custom Wordlist Can Be Used~~
- **Reverse IP Domains Check**
  - Unlimited API
- **SQL Injector**
  - WAF Bypass
  - Error Based  
  - ~~Union Based~~
- **Subdomains Enumerations**
  - Unlimited API
  - ~~BruteForce With Wordlist~~
## Download & Installation
```
$ git clone https://github.com/1337r0j4n/webin.git
$ cd webin
$ bash webin.sh
```
### In One Shot
```
 mkdir webin; cd webin; wget https://raw.githubusercontent.com/1337r0j4n/webin/main/webin.sh; bash webin.sh
```

**If webin on linux it's need root permission to install require packages**
### Dependencies Packages
```bash
dependencies_pkg()
{
    pkg=(grep curl dnsutils wget sed awk vim xxd)
        for pkg in "${pkg[@]}";do
            command -v $pkg >/dev/null 2>&1 || apt-get install $pkg -y
        done
}
```
### Workflow of Webin 
<p align="center">
<img src="https://raw.githubusercontent.com/1337r0j4n/webin/main/demo.gif">
</p>


