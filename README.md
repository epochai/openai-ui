# MyChatGPT

This is a OSS standalone ChatGPT client. It is based on [ChatGPT](https://openai.com/blog/chatgpt).


## Hosted Version

You can use the hosted version of this client [here](https://my-chat-gpt-lake.vercel.app/).

## Installation

Go to the [realease page](https://github.com/Loeffeldude/my-chat-gpt/releases) and download and install the latest release for your platform.

## Setup

1. Head over to the settings and enter your OpenAI API key. You can get one [here](https://platform.openai.com/account/api-keys).

2. Choose a preamble. A basic default preamble is already set. You can change it to something more specific to your use case.

3. Start Chatting!

---


## Features

### Pay as you go.

You use your own API key and pay for the usage this turns out to be much cheaper than the original ChatGPT website with moderate usage.

### More customization.

You can change the models behaior by changing the preamble. You can use this to create more customized chatbots.

### Edit the chat history.

You can edit the chat history and the model will continue the conversation from the edited point.

### Mark messages as important.

You can mark messages as important. Important messages will never be dropped from the conversation. (The model still has a token limit all not important messages will be dropped if the conversation gets too long.)

### No annoying login flow.

You can use the client without having to login to OpenAI.

---

## Development

This is just a React app with an Electron wrapper.

Building is done with Vite.

Fork this repo and start hacking. Feel free to open a PR if you want to contribute.

### Setup

```bash
npm install
```

### Run

```bash
npm run dev
```

### Build

Build the electron app:

```bash
npm run build:electron
```

Just build React app:

```bash
npm run build:client
```
