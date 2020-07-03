
2020.06.29 Changed by Hwang
========================================

Requirements and Enviroments

1. Cross Desktop Enviroments
    1) Ubuntu 16.04 x64
    2) openssl 1.0.2g
	3) Qt 5.6.2
	4) Qt Creator 4.7.2
	5) gcc 6.5
	6) qt sqlite3 driver based wxSQLite3 - 0.6
	7) sqlcipher 4.4.0
	8) additional cipher algorithm is ARIA of KISA
	
2. Target Environments
    1) nitrogen6x x32
    1) Freescale i.MX6 Quad/DualLite - ARMv7 Processor rev 10 (v7l)
    2) buildroot 2017.02.11
	3) openssl 1.0.2o
	4) Qt 5.6.3
	5) Qt Creator 4.7.2
	6) gcc 6.4(arm-linux-gnueabihf)
	7) qt sqlite3 driver based wxSQLite3 - 0.6
	8) sqlcipher 4.4.0
	9) additional cipher algorithm is ARIA of KISA
	
3. comment by hwang
I referenced most code with tag version 0.6 of "https://github.com/devbean/QtCipherSqlitePlugin.git".
Because upper version than 0.6 version is not compiled within Qt 5.6.2 ~ 5.6.3 of my environments.




QtCipherSqlitePlugin
====================

A Qt plugin for cipher SQLite which is based on SQLite source and wxSQLite3 in wxWidget.

Qt is a full development framework with tools designed to streamline the creation of applications and user interfaces for desktop, embedded and mobile platforms. You could find more details at https://www.qt.io.

SQLite is a software library that implements a self-contained, serverless, zero-configuration, transactional SQL database engine. SQLite is the most widely deployed SQL database engine in the world. The source code for SQLite is in the public domain. You could find more details at http://www.sqlite.org/.

wxSQLite3 is a C++ wrapper around the public domain SQLite 3.x database and is specifically designed for use in programs based on the wxWidgets library. wxSQLite3 includes an optional extension for SQLite supporting key based database file encryption using 128 bit AES encryption. You could find more details at http://utelle.github.io/wxsqlite3. wxSQLite3 is released under wxWindows Library Licence.

You could find how to compile this plugin at http://qtciphersqliteplugin.galaxyworld.org.

Please read [Wiki](https://github.com/devbean/QtCipherSqlitePlugin/wiki) for more details.



