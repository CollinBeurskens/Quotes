# Random Quote App

This is a simple web app that fetches a random quote from a JSON file and displays it on the page. The user can also download the displayed quote as a `.txt` file.

## `quotes.json` Structure

The `quotes.json` file is where all the quotes are stored. It must follow a specific structure to be used correctly by the app.

### Structure:

```json
{
  "quotes": [
    {
      "quote": "The only way to do great work is to love what you do.",
      "author": "Steve Jobs"
    },
    {
      "quote": "In the middle of every difficulty lies opportunity.",
      "author": "Albert Einstein"
    },
    {
      "quote": "Success is not the key to happiness. Happiness is the key to success.",
      "author": "Albert Schweitzer"
    }
  ]
}
