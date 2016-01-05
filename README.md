# PR Status

The goal of this project is to scan a GitHub repo for open pull requests
and analyze them, printing their conflict status, number of comments, etc...


## Requirements

`prstatus` is written in Bash and depends on [`jq` for JSON projecessing](https://stedolan.github.io/jq/)
and [`curl` for API interaction](https://github.com/bagder/curl).
