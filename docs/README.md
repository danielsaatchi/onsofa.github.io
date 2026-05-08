#  Dynamic-GPT theme by 🛋️ONOSOFA.ai

This is a simple multi-page website that demonstrates a ChatGPT-style typing
animation. All key text elements (headers, navigation links, paragraphs, and
some form elements) are animated from left to right.

## Repository layout

```
onsofa/docs/
├── index.html                 # Home page (main page)
├── projects.html              # Projects page
├── publications.html          # Publications page
├── products.html              # Products page
├── contact.html               # Contact-us page
├── style.css                  # All CSS rules
├── typing.js                  # Typing animation logic
├── style.css                  # All CSS rules
├── README.md                  # Instruction
├── CODE_OF_CONDUCT.md         # Opensource note
└── fonts/
    └── CascadiaCode-Regular.woff2   # Optional – if not from URL (check .css file)
```

## How the Typing Works

Any element with the `type-line` class will be animated:
```html
<h1 class="type-line" data-delay="0">
  Dynamic-GPT theme by 🛋️ONOSOFA.ai
</h1>
