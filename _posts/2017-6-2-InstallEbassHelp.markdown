---
layout: post
title:  "Installation of Ebaas"
date:   2017-6-2
---

<p class="intro"><span class="dropcap">E</span>baas is an enterprise application for Testing Data Management (TDM). Testing Data Management software in product testing fields can shorten the product test cycle, reduce test costs, accelerate market-to-market. </p>

<p>In this post, you will find the instructions for installing the Ebaas (out-of-the-box version), launching the application server, and log in using one of the demo accounts. If you ran into problems, please refer to "FAQ" page for possible solutions.</p>

## Installation Requirements

First of all, please make sure your installation environment meets the following requirements.

* Your computer is running one of operating systems, such as Windows 7 (x64), Windows 10 (x64), Windows 2008 (x64)
* Your computer has installed Microsoft.Net Framework 4.5.2
* Your computer has one of the web browsers, such as Google Chrome,  Windows Edge, or IE 11

## Installations

Run the downloaded Ebaas_x64_7.1.0_beta2_Setup.msi as the Administrator, follow the steps until the installation is complete. The out-of-the-box version has an embedded SQL Server Compact database, therefore, you don't need to install a database.

## Launch Application Server

Find the command at Start->Ebaas->StartServer and click on the command to launch the application server. Please run the command as the administrator on Windows 7 or Windows 10, and You will see the command windows shown in Figure 1 if the application server started successfully. To stop the application server, just close the command window.

<img src="{{'/assets/img/2017-06-01-Fig1.png' | prepend: site.baseurl }}" alt="">

Figure1. - Application Server Window

## Login to Ebaas

Use a recommended web browser to connect to the application at <code>http: // localhost: 8080</code>.  The login page should appear shown in Figure 2.  You can use any of the following demo user accounts to log in and explore the features of Ebaas.

| User ID | Password | User Role |
|-------|--------|---------|
| demo1 | 888 | Administrator |
| demo2 | 888 | Lab manager |
| demo3 | 888 | Lab operator |

<img src="{{'/assets/img/2017-06-01-Fig2.png' | prepend: site.baseurl }}" alt="">

Figure2. - Log in page

## License

Copyright (c) 2017 Yong Zhang

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.