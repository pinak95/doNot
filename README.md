# doNot - Notion and Todoist Integration

doNot is a simple and convenient Python-based integration tool that bridges the gap between Notion and Todoist. With doNot, you can seamlessly synchronize your tasks and projects between these two popular productivity apps. This guide will walk you through the process of setting up and using doNot to streamline your task management.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Bi-Directional Sync:** Changes made in Todoist are reflected in Notion, and vice versa.
- **Task Mapping:** Tasks added in Todoist can be mapped and mirrored to specific pages or projects in Notion.
- **Easy Setup:** A straightforward setup process to establish the connection between Notion and Todoist.

## Prerequisites

Before you begin, make sure you have the following:

1. A Notion account with API access. You can sign up for API access at [Notion Integrations](https://www.notion.so/my-integrations).
2. A Todoist account.
3. Python 3.6 or higher installed on your system.

## Installation

1. Clone the doNot repository from GitHub:

```bash
git clone https://github.com/yourusername/doNot.git
```

2. Install the required Python packages:

```bash
pip install -r requirements.txt
```

## Getting Started

1. **Todoist API Setup:**
   - Go to the [Todoist Developer Console](https://developer.todoist.com/appconsole.html).
   - Create a new app and note down the `Client ID` and `Client Secret`.
   - Set the OAuth Redirect URL to `https://todoist.com/oauth/authorize?client_id=CLIENT_ID&scope=task:add,data:read_write,data:delete,project:delete&state=STATE`.

2. **Notion API Setup:**
   - Obtain your Notion integration token from [Notion Integrations](https://www.notion.so/my-integrations).

## Usage

1. Run the `integration.py` script:

```bash
python integration.py
```

2. Follow the on-screen prompts to complete the OAuth flow for Todoist.

3. Watch as your tasks and projects are seamlessly synchronized between Notion and Todoist.

## Contributing

Contributions to doNot are always welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test thoroughly.
4. Create a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Enjoy the convenience of managing your tasks and projects across Notion and Todoist using doNot. If you encounter any issues or have questions, feel free to reach out to me on GitHub. Let's get productive together.

*Disclaimer: This project is not affiliated with or endorsed by Notion or Todoist.*
