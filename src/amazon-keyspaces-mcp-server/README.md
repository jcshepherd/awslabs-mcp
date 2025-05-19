# AWS Labs amazon-keyspaces MCP Server

An Amazon Keyspaces (for Apache Cassandra) MCP server for interacting with Amazon Keyspaces and Apache Cassandra.

## Features

The Amazon Keyspaces (for Apache Cassandra) MCP server provides the following capabilities:
1. **Schema**: Explore keyspaces and tables.
2. **Run Queries**: Execute CQL SELECT queries against the configured database.
3. **Query Analysis**: Get feedback and suggestions for improving query performance.
4. **Cassandra-Compatible**: Use with Amazon Keyspaces, or with Apache Cassandra.

Here are some example prompts that this MCP server can help with:
- "List all keyspaces in my Cassandra database"
- "Show me the tables in the 'sales' keyspace"
- "Describe the 'users' table in the 'sales' keyspace"
- "What's the schema of the 'products' table?"
- "Run a SELECT query to get all users from the 'users' table in 'sales'"
- "Query the first 10 records from the 'events' table"
- "Analyze the performance of this query: SELECT * FROM users WHERE last_name = 'Smith'"
- "Is this query efficient: SELECT * FROM orders WHERE order_date > '2023-01-01'?"

## Instructions



## TODO (REMOVE AFTER COMPLETING)

* [ ] Optionally add an ["RFC issue"](https://github.com/awslabs/mcp/issues) for the community to review
* [ ] Generate a `uv.lock` file with `uv sync` -> See [Getting Started](https://docs.astral.sh/uv/getting-started/)
* [ ] Remove the example tools in `./awslabs/amazon_keyspaces_mcp_server/server.py`
* [ ] Add your own tool(s) following the [DESIGN_GUIDELINES.md](https://github.com/awslabs/mcp/blob/main/DESIGN_GUIDELINES.md)
* [ ] Keep test coverage at or above the `main` branch - NOTE: GitHub Actions run this command for CodeCov metrics `uv run --frozen pytest --cov --cov-branch --cov-report=term-missing`
* [ ] Document the MCP Server in this "README.md"
* [ ] Add a section for this amazon-keyspaces MCP Server at the top level of this repository "../../README.md"
* [ ] Create the "../../doc/servers/amazon-keyspaces-mcp-server.md" file with these contents:

    ```markdown
    ---
    title: amazon-keyspaces MCP Server
    ---

    {% include "../../src/amazon-keyspaces-mcp-server/README.md" %}
    ```
  
* [ ] Reference within the "../../doc/index.md" like this:

    ```markdown
    ### amazon-keyspaces MCP Server
    
    An Amazon Keyspaces (for Apache Cassandra) MCP server for interacting with Amazon Keyspaces and Apache Cassandra.
    
    **Features:**
    
    - Feature one
    - Feature two
    - ...

    TODO
    
    [Learn more about the amazon-keyspaces MCP Server](servers/amazon-keyspaces-mcp-server.md)
    ```

* [ ] Submit a PR and pass all the checks
