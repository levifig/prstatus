# PR Status

Quickly get a list of open pull request from any repository or details about a specific one.

## Usage
```bash
./prstatus [-dh] [-t TOKEN] [-r REPO]...
Options:
    -h | --help                 display this syntax information and exit
    -d | --debug                display API request details and exit
    -t | --token TOKEN          OAuth token **(required)**
                                  More info: http://git.io/vmNUX
                                  Example:  ./prstatus -t e72e16c7e42f292c6912e7710c8
    -r | --repo USER/REPO       Target repository **(required)**
                                  Note: specify repo\'s owner username OR organization
                                  Example:  ./prstatus -r reddit/reddit
                                            ./prstatus -r levifig/prstatus
    -p | --pullrequest ID       Specify unique pull request by its ID (requires specific repo)
                                  Example:  ./prstatus -r reddit/reddit -p 1449
```

## Requirements

`prstatus` is written in Bash, requires Bash 4.x or higher, and depends on [`jq` for JSON projecessing](https://stedolan.github.io/jq/) and [`curl` for API interaction](https://github.com/bagder/curl).
