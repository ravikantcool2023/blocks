# Blocks platform

Hello! Thanks for participating in the developer preview of the Airtable Blocks platform! Before
today, all blocks were developed by Airtable. No longer! You're now able to supercharge your own
workflows.

By participating in the developer preview and using the software, you accept and agree to abide by
terms of the [developer preview agreement](/DEVELOPER_AGREEMENT.md).

## If you're new to writing blocks

1. First, follow our [getting started guide](/packages/sdk/docs/setup.md). You'll learn how to get
   your blocks dev environment set up, and how to write a "Hello, World" block.

2. Follow our [guide to writing a to-do list block](/packages/sdk/docs/tutorial_todo.md). You'll
   learn how to query and display data from your base, how to use core Airtable functions like
   "expand record", how to use the built in component library to let the user choose a table, and
   how to store user preferences.

## If you want to figure out how to do something specific

### API documentation

The [API reference](https://github.com/Airtable/blocks/tree/master/packages/sdk/docs/api.md)
documents public methods and code examples.

## Support

We'd love to hear all your feedback! If you run into any bugs, find anything confusing, or have
questions or feature requests you can email the platform engineering team directly at
<blocks@airtable.com>.

### Example block source code

Here is the code for several example blocks. You can read it to learn techniques and see best
practices for blocks development. And you can use it as a jumping off point for your own blocks.

-   [Simple chart](https://github.com/Airtable/blocks/tree/master/examples/simple_chart) - Shows a
    bar chart of base data using the Chart.js external library.
-   [To-do list](https://github.com/Airtable/blocks/tree/master/examples/todo) - The code for the
    to-do list example from the guide above.
-   [Summary](https://github.com/Airtable/blocks/tree/master/examples/summary) - Uses the built-in
    summary functions (average, max, etc.) on a table field.
-   [YouTube preview](https://github.com/Airtable/blocks/tree/master/examples/youtube_preview) -
    Uses the Cursor API to detect when the user selects a record in grid view. Gets a YouTube URL
    from the record and plays the corresponding video.

##### Simple chart

[![Block updating chart as the user changes data](examples/simple_chart/media/block.gif?raw=true)](examples/simple_chart)

##### To-do list

[![Block updating to-do list as the user changes data](examples/todo/media/block.gif?raw=true)](examples/todo)

##### Summary

[![Block updating summaries as the user changes data](examples/summary/media/block.gif?raw=true)](examples/summary)

##### YouTube preview

[![Block showing YouTube video when user selects record in grid view](examples/youtube_preview/media/block.gif?raw=true)](examples/youtube_preview)
