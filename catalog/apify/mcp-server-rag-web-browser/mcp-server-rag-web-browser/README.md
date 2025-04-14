
# Model Context Protocol (MCP) Server for the RAG Web Browser Actor 🌐

A containerized version of "Model Context Protocol (MCP) Server for the RAG Web Browser Actor 🌐"

> Repository: [apify/mcp-server-rag-web-browser](https://github.com/apify/mcp-server-rag-web-browser)

## Description

Implementation of an MCP server for the [RAG Web Browser Actor](https://apify.com/apify/rag-web-browser).


## Usage

The containers are built automatically and are available on the GitHub Container Registry.

1. Pull the Docker image:

```bash
docker pull ghcr.io/metorial/mcp-container--apify--mcp-server-rag-web-browser--mcp-server-rag-web-browser
```

2. Run the container:

```bash
docker run -it --rm ghcr.io/metorial/mcp-container--apify--mcp-server-rag-web-browser--mcp-server-rag-web-browser 
```

- `--rm` removes the container after it exits, so you don't have to clean up manually.
- `-it` allows you to interact with the container in your terminal.


### Configuration

The container supports the following configuration options:




#### Environment Variables

- `APIFY_TOKEN`




## Usage with Claude

```json
{
  "mcpServers": {
    "mcp-server-rag-web-browser": {
      "command": "docker",
      "args": [
        "run",
        "-it",
        "--rm",
        "ghcr.io/metorial/mcp-container--apify--mcp-server-rag-web-browser--mcp-server-rag-web-browser"
      ],
      "env": {
        "APIFY_TOKEN": "apify-token"
      }
    }
  }
}
```

# License

Please refer to the license provided in [the project repository](https://github.com/apify/mcp-server-rag-web-browser) for more information.

## Contributing

Contributions are welcome! If you notice any issues or have suggestions for improvements, please open an issue or submit a pull request.

<div align="center">
  <sub>Containerized with ❤️ by <a href="https://metorial.com">Metorial</a></sub>
</div>
  