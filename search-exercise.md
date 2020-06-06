# Build a hybrid search

We would like to develop a hybrid search in the Folloze platform. A search that will return more than one entity type as part of its result.

Our search should support both Boards and Items:

![design](https://images.folloze.com/image/upload/v1590933908/index_okjstn.png)

### Requirements
- Use the `search.html` below to build the experience above.
- Use the supplied `<script>` `<style>` `<body>` elements. No third party frameworks, libraries, or external resources.
- Use Vanila JS for implementation.
- When clicking on a Board search result it should log in the console: "Board #{board.id} was clicked!"
- When clicking on an Item search result it should log in the console: "Item #{item.id} was clicked!"

**Note:** Although your entire code is under one script tag, try to find the needed abstractions and organize your code. Think of the data as if it's an asyc request away.

### Submission
- **Don't fork this gist** as that would make your solution public for others to see. Instead, save a copy of `search.html` and work on it locally.
- When you're done, create a new private gist with your solution and send us the link.
- The submitted HTML should be run without errors when launched in the browser.