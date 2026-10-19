# uBlockOrigin AI-Assistant-Blocklist

A blocklist of **conversational AI assistant** websites (ChatGPT, Gemini, Claude, Le Chat, Perplexity, Copilot, Grok, Duck.ai, DeepSeek, Meta AI…), adapted from [laylavish/uBlockOrigin-HUGE-AI-Blocklist](https://github.com/laylavish/uBlockOrigin-HUGE-AI-Blocklist).

## Installation (uBlock Origin)

1. Open the uBlock Origin dashboard → **Filter lists** tab → **Import**.
2. Paste the URL of the list you want:
   ```
   https://raw.githubusercontent.com/luc4rto/AI-Assistant-Blocklist/main/list.txt
   ```
3. **Apply changes**. uBO refreshes the list automatically once a day.

## Installation (uBlacklist)

1. Extension options → **Subscriptions** → **Add a subscription**.
2. URL:
   ```
   https://raw.githubusercontent.com/luc4rto/AI-Assistant-Blocklist/main/list_uBlacklist.txt
   ```
3. Set the update interval to 1 hour, and enable your search engines under "Other search engines".

## Covered sites
   Category | Sites |
 |---|---|
 | General-purpose assistants | ChatGPT, Gemini, Claude, Le Chat (Mistral), Perplexity, Duck.ai, Microsoft Copilot, Grok, DeepSeek, Meta AI, Poe, You.com, Kimi, Qwen, Z.ai/GLM, Ernie, HuggingChat, Pi, Google AI Studio, NotebookLM, Kagi Assistant |
 | Companion / roleplay chatbots | Character.AI (+ c.ai), Janitor AI, SpicyChat, Replika, Chai, CrushOn |

## Contributing

Feel free to fork and submit a PR if you find more sites. To add a site like `chat.example.com`:

- `list.txt`: `||chat.example.com^`
- `list_uBlacklist.txt`: `*://*.chat.example.com/*`