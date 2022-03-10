```json
{
  "div": [
    "#id:card-front",
    ".class:card-front front",
    "@events:",
    {
      "foreach": [
        "@data: eqpo/-/display.json::posts",
        {
          "div": [
            "#key: %index"
            ".class: post-front",
            "@events:"
          ]
        }
      ]
    }
  ],
  "events": [
    {
      "click-things": [
        "@type: click",
        "!bubble",
        "!self",
        "!recipient: []"
      ]
    }
  ],
  "recipient": [
    {
      "post": [
        "#key: ",
        ".class: post-front"
      ]
    }
  ]
}
```
