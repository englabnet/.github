# Welcome!

This organisation is dedicated to [Englab](https://englab.net), a website for English learners. Here, you can find all the public source code for the project.

## Overview

Here's a short overview of the public repositories:

* 🔍 [context-searcher](https://github.com/englabnet/context-searcher) is an application responsible for the runtime of the search functionality on the website. Currently, it only supports searching for words and phrases through subtitles in YouTube videos.
* 🔍 [indexer](https://github.com/englabnet/indexer) is an indexing application for the context-searcher. It exposes REST endpoints for adding, updating, and removing videos, as well as performing full reindexing.
* 📚 [search-common-lib](https://github.com/englabnet/search-common-lib) is a library that contains common classes for the indexer and the context-searcher.
* ✍️ [spelling-trainer](https://github.com/englabnet/spelling-trainer) is an application that handles spelling tests. It provides REST endpoints for creating new spelling tests and taking them.
* 📨 [feedback-collector](https://github.com/englabnet/feedback-collector) is a small application that collects feedback from Englab users.
* 📡 [gateway](https://github.com/englabnet/gateway) is an application for routing requests to other services. It's also responsible for rate limiting, CAPTCHA and security.
* 🌐 [website](https://github.com/englabnet/website) is a React application that represents the UI of Englab.
* 🔑 [admin-console](https://github.com/englabnet/admin-console) is a React application that represents the UI of the admin console. The interface enables adding, updating, and removing videos, performing full reindexing, and accessing users' feedback.

## Contributing

This is mostly a solo project that I'm working on just for fun in my spare time. However, if you're really interested and would like to join me in developing new features, I'd love to hear from you! Feel free to reach out via email at <nikitakuchur@gmail.com>.
