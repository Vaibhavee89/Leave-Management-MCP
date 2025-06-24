# Leave Management MCP Server

This is a simple **Leave Management MCP (Model Context Protocol) Server** designed for educational purposes. It integrates with **Claude Desktop** and allows management of leave requests through a customized MCP interface. The project follows a minimal setup to help beginners learn MCP server development.

---

## 🚀 Features

- Leave application management via CLI and Claude Desktop
- Simple and customizable MCP server structure
- Beginner-friendly setup
- Built as a learning project inspired by a YouTube tutorial

---

## 🛠️ Setup Instructions

Follow these steps to set up and run the Leave Management MCP Server:

1. **Install Claude Desktop**  
   Download and install Claude Desktop from the official website.

2. **Install `uv` package manager**  
   ```bash
   pip install uv


3. **Initialize a new MCP server project**

   ```bash
   uv init my-first-mcp-server
   ```

4. **Add MCP CLI dependency to your project**

   ```bash
   uv add "mcp[cli]"
   ```

5. **(Optional)** Fix potential typing errors by upgrading `typer`

   ```bash
   pip install --upgrade typer
   ```

6. **Implement the server logic**
   Write your leave management server code in `main.py`.

7. **Install this MCP server inside Claude Desktop**
   Run the following in the project directory:

   ```bash
   uv run mcp install main.py
   ```

8. **Restart Claude Desktop**

   * Kill any running instance of Claude from **Task Manager**.
   * Start Claude Desktop again.

9. **Set the tool in Claude Desktop**
   You can now configure and use this server as a tool inside Claude Desktop.





## 🖼️ Sample Claude Responses

Below are sample responses from Claude Desktop while interacting with this MCP server:

### Image 1: Leave Query

![Claude Leave Request](/LeaveManagementSS1.png)

### Image 2: Apply for Leave Approval Response

![Claude Leave Approval](/LeaveManagemetntSS2.png)





