## A command line file uploader for Fileslap

### Installation

- [Install python-requests](http://docs.python-requests.org/en/latest/user/install/) (it's the only dependency).
- Download the "fileslap" script.
- Edit the script, replacing YOURUSERNAME and YOURPASSWORD with your login info.
- Make it executable:
    `$ chmod o+x ./fileslap`
- Move the script to /usr/local/bin/

### Usage

    $ fileslap yourfilename

### Result

The link to the file (both on the site and the raw file) will be output to stdout, like this:

    URL: http://fileslap.com/7Hi/index
    Raw: http://media.fileslap.com.s3.amazonaws.com/7Hi/index.html

