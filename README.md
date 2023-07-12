# Go websockets server chat thing

A super simple barebones websockets chat server and client. I've been learning some Go and just wanted a little project to test my knowledge.

This is by no means a complete, hardened, tested package. God help you if you try to use this in production.

## Instructions

Pull down dependencies with something like

```sh
go mod tidy
```

Run the thing (you probably don't want to bother building/installing this) - it'll start on port `3000`

```sh
go run .
```

In your web browser navigate to `http://localhost:3000` to load the chat UI
