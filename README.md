# twitter-archive-reader
Simple reader for direct messages from twitter's anonymized archives.

The reader is built with Vue, and is optimized for reading large chat histories by dividing up conversations into days.
By unzipping your twitter archive into the `archive/` directory sibling to the `chat.html` you may read the entire contents of the chat history.

Requirements are not included in this repository at the moment, instead relying on remote CDNs.  If you wish for a completely offline version, you may download the dependencies and modify the html to point to local copies.
