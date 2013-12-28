Phalcon Windows X64 VC11 DLL
====================

Php Windows binary extension for Phalcon 1.2.4 for PHP 5.5 VC11 64 Bit.

I build the extension for Thread Safe and Not Thread Safe PHP Environment.

I tested the extension on: 
- Windows 8.1
- PHP 5.5.7 nts VC11 X64 (http://windows.php.net/downloads/releases/php-5.5.7-Win32-VC11-x64.zip)
- CGI Mode

Installation 
======
1. Download the nts or the ts package (depending from you PHP Environment). 
2. Extract zip package.
3. Copy the php_phalcon.dll in your extension dir.
4. Add "extension=php_phalcon.dll" to your php.ini (without quotes).
5. Restart Php service (if already executing in FastCgi o IIS)

How to build
======
To build this extension I followed these tutorials:
- http://szdredd.blogspot.cz/2013/11/how-to-setup-phalcon-framework-under.html ( Author of compiled x86 version of this extension)
- https://wiki.php.net/internals/windows/stepbystepbuild (Official PHP Windows Build tutorial)
- http://internals.phalconphp.com/en/latest/reference/compilation.html (Official Phalcon Build tutorial)

Source Code
======
You can download the source code from the official phalcon repository: https://github.com/phalcon/cphalcon

32bit ( X86 ) Edition
======
If you are looking for X86 PHP 5.5 (32bit) extension version, you can look this repository: https://github.com/andont/phalcon-win
