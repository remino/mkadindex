mkdldir
=======

```
mkdldir 1.0.0

USAGE: mkdldir [-ahprtuv] <outputdir>

Create password-protected download directory for Apache.

Directory will be created in <outputdir> and protected using HTTP Digest with
a pair of .htdigest and .htaccess files.

OPTIONS:

	-a        Specify absolute path base to .htaccess file to use.
	          Path will become <pathbase>/<outputdir>/.htaccess.
	          If not specified, will only <outputdir>/.htaccess.
	          (Note AuthUserFile in .htaccess cannot be relative.)
	-h        Show this help screen.
	-p        Specify password for digest authentication. (Required.)
	-r        Specify realm for digest authentication. (Default: Download)
	-t        Specify title for directory. (Default: Download)
	-u        Specify username for digest password. (Default: download)
	-v        Show script name and version number.

```

