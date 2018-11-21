# Banks CLI 🏦

I hate bank software. It's horrible, slow and annoying to deal with. This project is my attempt at making my life a bit easier. It's a simple command line tool that helps me out with the following tasks

 - Navigate to the transfer page.
 - Export monthly reports.
 - Covert exported files (csv, xsl) to unified csv.
 
## Instructions:

1. Install pipenv.
2. Clone the repository.
3. Get the Selenium chromedriver
4. Create a `config.ini` file based on `config.ini.example`.
5. run `./banks`

## Example

```
$ ./banks
usage: banks.py [-h] {transfer,export,convert} ...

Access your banks in a jiffy. 🚀

optional arguments:
  -h, --help            show this help message and exit

Options:
  {transfer,export,convert}
                        Choose an action to perform.
    transfer            Create a new domestic transfer. 💸
    export              Export transactions. 📋
    convert             Convert exported transactions. 🔁
```
