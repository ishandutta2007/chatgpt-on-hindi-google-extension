# arXivGPT

A browser extension to display ChatGPT response alongside Google (and other search engines) results

[Install from Chrome Web Store](https://chatgpt4google.com/chrome?utm_source=github)

[Install from Mozilla Add-on Store](https://chatgpt4google.com/firefox?utm_source=github)


## Screenshot

<img width="1418" alt="image" src="https://user-images.githubusercontent.com/901975/217130285-20d0bf67-e9a8-46ca-9d9d-f49b42515a7d.png">

## Custom Prompt
You can change the prompt.
<img width="1031" alt="image" src="https://user-images.githubusercontent.com/901975/217131081-d5487c3f-cb5c-46f4-be21-e4f1a22e9fce.png">

## Troubleshooting

### How to make it work in Brave

![Screenshot](screenshots/brave.png?raw=true)

Disable "Prevent sites from fingerprinting me based on my language preferences" in `brave://settings/shields`

### How to make it work in Opera

![Screenshot](screenshots/opera.png?raw=true)

Enable "Allow access to search page results" in the extension management page

## Build from source

1. Clone the repo
2. Install dependencies with `npm`
3. `npm run build`
4. Load `build/chromium/` or `build/firefox/` directory to your browser

## Credit

This project is inspired by [ZohaibAhmed/ChatGPT-Google](https://github.com/ZohaibAhmed/ChatGPT-Google) and https://github.com/wong2/chatgpt-google-extension
