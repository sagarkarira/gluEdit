# gluEdit 

[![Status: development](https://img.shields.io/badge/status-development-yellow.svg)](https://opensource.org/licenses/MIT) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


Another real time collabrative editor based on **Logoot CRDT algorithm.**

![gluEdit](https://media.giphy.com/media/xT9IgDIoMnoo6fXvWw/giphy.gif)

## Getting Started


### Prerequisites

* Node 8 or above
* Redis Server

### Installing


* ``npm install``

* ``NODE_ENV=development node app.js``

* Open ``http://localhost:8000/`` in your browser to get started.

### Todos 

- <s>Save versions of content at frequent interval.</s>
- Frontend : Check for new version at regular interval. (Ajax call)
- Save version for long documents more efficiently.
- Dont save  version if document/editor is idle.
- Listen for Undo, Paste, and selection deletion text change events for code mirror text box.
- Not allow duplicate users.
- Refactor, Writing Documentation and Tests


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


