# Nerd Chat
A terminal based peer to peer application using [pears](https://pears.com/).

## Getting Started
Follow the documentations [getting started](https://docs.pears.com/guides/getting-started) instructions to prepare your environment.

## Run Application

### Development
Chat Host:
```
pear run pear://ty16mqbnxj3qb66gumkpmkpme4cq4mo787iawyadzczwszckonyy
```
A message will appear:
```
[info] Created new chat room: [key]
```
Share the key with another terminal or another user:
```
pear run pear://ty16mqbnxj3qb66gumkpmkpme4cq4mo787iawyadzczwszckonyy [key]
```
A secure peer to peer (p2p) connection is made in the terminal.

### Chat instructions
A `>` indicates a chat prompt.  
`Return` submits a message.
Submitting a message of `exit` exits the chat.
