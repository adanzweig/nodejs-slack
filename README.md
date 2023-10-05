# Slack Message Sender

A Node.js script to send messages to a Slack channel using the Slack Web API.

## Prerequisites

Before running the script, make sure you have the following:

- Node.js installed on your machine.
- A Slack workspace where you have the permissions to create a Slack app.

## Setup

1. Clone this repository:

    ```bash
    git clone https://github.com/adanzweig/nodejs-slack.git
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the project root and add your Slack API token and channel ID:

    ```env
    SLACK_TOKEN=your_slack_api_token
    CHANNEL_ID=your_slack_channel_id
    ```

## Usage

Run the script using the following command:

```bash
node index.js
```

This will send a test message to the specified Slack channel.

## Configuration

- **SLACK_TOKEN**: Your Slack app's Bot token obtained from the Slack API.
- **CHANNEL_ID**: The ID of the Slack channel where you want to send messages.

## Contributing

Feel free to contribute to the project by opening issues or submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Make sure to replace the placeholder values (e.g., `your_slack_api_token`, `your_slack_channel_id`, etc.) with the actual values relevant to your Slack app and channel.