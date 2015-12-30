# PR Status

The goal of this project is to scan a GitHub repo for open pull requests
and analyze them, printing their conflict status, number of comments, etc...


## Requirements

To run `prstatus`, you must first make it executable: `chmod +x prstatus`.

`prstatus` is written in Bash and depends on [\`jq\` for JSON projecessing](https://stedolan.github.io/jq/)
and [\`curl\` for API interaction](https://github.com/bagder/curl).
