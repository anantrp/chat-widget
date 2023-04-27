<img src="https://user-images.githubusercontent.com/1721988/234579578-398aab55-9336-4a20-aa62-319cf1bf4a99.png" height="80" width="auto">

<h1>Web Chat Widget</h1>

Easily add a chat bubble to your website with a single `script` tag. A simple and responsive chat widget built with HTML, CSS, and JavaScript. The chat widget is styled using Tailwind CSS (v2). [The blog post](https://anantrp.hashnode.dev/how-i-built-a-chat-widget-with-chatgpt-in-under-an-hour) describing how I did it.

## Built with ChatGPT (GPT-4)

About 95% of the code for this widget is written by GPT-4, I just edited and adjust a few things


<br>

<p align="left">
<img src="https://user-images.githubusercontent.com/1721988/234564883-685d7e3f-8640-4d4d-8b42-3b7be18b59dc.gif"  height="320" width="auto">
<img src="https://user-images.githubusercontent.com/1721988/234564904-e7f02e30-cc7c-40db-9a2a-e123510f1283.gif"  height="320" width="600">
</p>

## Features

- No external dependencies, pure javascript
- Responsive design
- Smooth animations and transitions
- Easily customizable
- Lightweight and dependency-free

## TODO

- Replace Tailwind with a custom CSS file
- Session Persistance
- Ajax mechanism to send and receive messages

## Installation

To install the chat widget, follow these steps:

1. Copy the `chat-widget.js` file into your project directory.

2. Add the following script tag to the `<head>` section of your HTML document:

```
<script async src="./chat-widget.js"></script>
```

## Usage & Customization

- The code is quite straight forward and easy to follow, you can easily modify it to suit your needs.

- Messages are passed to the `onUserRequest` function, where you can handle user requests and provide appropriate replies. Use the `reply` function to display responses in the chat popup.

- For visual customization, you can directly make changes to the css or you can also replace the Tailwind CSS classes with your own custom CSS classes or inline styles.

## Demo

Here's a live demo of the chat widget:

[Chat Widget Demo](https://anantrp.github.io/chat-widget)

## Contributing

Contributions are welcome! If you find a bug, have a feature request, or want to improve the chat widget, please feel free to open an issue or create a pull request.

## License

This project is open-source and available under the [MIT License](https://choosealicense.com/licenses/mit/).
