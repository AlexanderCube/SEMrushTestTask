# SEMrushTestTask

<b>This repository for Tehnical writer job application (SEMrush) includes the instructions for opening HTML pages at the local environment and additional test.html page.</b>

|Version   |Date      |
|----------|----------|
|1.0.      |05.13.2019|

## Table of contents

1. <a href="#Introduction">Introduction</a>
2. <a href="#Command line utilization">Command line utilization</a>
3. <a href="#Local server utilization">Local server utilization</a>

<a name="Introduction"><h1><b>Introduction</b></h1></a>

The process of opening HTML pages at the local environment requires utilization of <b>Python<b> and <b>command line</b> terminal or application, which is available for Windows, Mac OS X and Linux.

<b>Note:</b> Installation of Python is required for Windows only. Mac OS X and Linux are provided with available packages. See <a href="#Command line utilization">Command line utilization</a> if the installation of Python is not required for current OS.

<b>Python installation for Windows</b>
1. Open the <a href="https://www.python.org">python.org</a> link and refer to <b>Downloads</b> section in order to download necessary installation packages. Click the link of provided installation package to continue. 
Example: <a href="https://www.python.org/downloads/release/python-373/">Python 3.7.3</a>.

2. Refer to <a href="https://www.python.org/ftp/python/3.7.3/python-3.7.3-amd64.exe">Windows x86-64 executable installer</a> which is available in <b>Files section</b> at the bottom of the page.

3. Download and launch <b>Windows x86-64 executable installer</b> in order to complete the installation. 
<b>Note:</b> Select the "Add Python 3.7.3 to PATH" checkbox before completing the installation.

<a name="Command line utilization"><b>Command line utilization</b></a>

The process of command line utilization requires launching of existing command line terminal or application and involvement of necessary commands which are described below.

1. Run the command line terminal or application, type <b>pip</b> command and press Enter.
Example: <b>C:\Users\alexander>pip</b>

2. Type <b>C:\Users\alexander>pip -V</b> in order to verify the installed version of Python and other required software packages.

<b>Note:</b> Type <b>pip install</b> in order to verify the neccessity for the update of required software packages. In case of receiving <b>You are using pip version 19.0.3, however version 19.1.1 is available.</b> message type <b>python -m pip install --upgrade pip</b> and press Enter in order to upgrade the existing software packages.
Example: <b>C:\Users\alexander\>python -m pip install --upgrade pip</b>

3. Add the test.html page file to the requested local directory. Type <b>cd</b> and input the address of local directory in order access the launching of required HTML page at the local environment.
Example: <b>C:\Users\alexander\Desktop>cd C:\Users\alexander\Documents\GitHub\SEMrushTestTask</b>

<a name="Local server utilization"><b>Local server utilization</b></a>

The process of local server utilization requires the involvement of necessary commands which are described below.

1. Type <b>python -m http.server 8000</b> and press Enter in order to launch local environment server and access the opening of test.html page in browser. This command allows accessing the local directory content on the local web server (port 8000).
Example: <b>C:\Users\alexander\Documents\GitHub\SEMrushTestTask>python -m http.server 8000</b>

2. Enter <a href="http://localhost:8000/">localhost:8000</a> in the address bar of the browser in order to check the confirmation of accessing the local directory.

3. Click the <b>test.html</b> link in order to open the requested page in the browser.

If <b>This is an example of a simple HTML page with one paragraph.</b> is displayed after clicking <b>test.html</b> link then the process of opening HTML pages at the local environment is complete and successful. In case of inability to open <b>test.html</b> link check the placement of <b>test.html</b> file in local directory or check the accessibility of local server by repeating procedures which are described in <a href="#Local server utilization">Local server utilization</a> section.
