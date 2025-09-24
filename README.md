### about 

A WordPress plugin that adds an AI chat box to any page via shortcode. It securely calls your Fireworks API on the server (key never exposed) and returns replies in a clean chat UI. Configure model, temperature, and tokens in Settings, then drop [fireworks_chatbot] into any page.

### Install the plugin
In WP Admin: Plugins → Add New → Upload Plugin → Choose File → Install Now → Activate.

### Configure settings
Go to Settings → Fireworks Chatbot and set:

API Key: fw_... (from your Fireworks account)

API URL: https://api.fireworks.ai/inference/v1/chat/completions

Model: accounts/fireworks/models/llama-v3p1-70b-instruct

Adjust Temperature, Max Tokens, Rate Limit if needed → Save Changes.

### Embed the chatbot
In any page/post, add a Shortcode block:

```bash
[fireworks_chatbot]
```
