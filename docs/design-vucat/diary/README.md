```json
{
  "div": [
    "#card-front",
    ".card-front .front",
    "@events:",
    {
      "foreach": [
        "@data: eqpo/-/display.json",
        {
          "div": [
            "@key: %index"
            ".post-front-%class",
            "@events: %event"
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
        {
          "recipient": [
            "group: post",
            "#viewpath"
          ]
        }
      ]
    }
  ],
  "recipient": [
    {
      "post": [
        "#key: ",
        ".post-front"
      ]
    }
  ]
}
```
