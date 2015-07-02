HtmlEntities
============

Elixir module for decoding HTML entities in a string.

## Usage

```elixir
    iex> HtmlEntities.decode("Tom &amp; Jerry")
    "Tom & Jerry"
    iex> HtmlEntities.decode("&#161;Ay, caramba!")
    "¡Ay, caramba!"
```
