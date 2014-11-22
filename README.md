#almost-inline.css

A collection of inline-like CSS classes. It is not the best practice to use this CSS. Use it responsibly.

##margin, padding
- {margin|padding}-{0|reset}
- {margin|padding}-{left|right|top|bottom}-0
- {margin|padding}-{left|right|top|bottom}-{n*5}px (1<=n<=20)
- {margin|padding}-{left|right|top|bottom}-{n*0.5}em (1<=n<=10)

##border, border-color
- border-{0|none}
- border-{n}px (0<n<=5)
- border-{left|right|top|bottom}-{n}px (1<=n<=5)
- border-color-{nnn|color} (0<=n<=F, color: any color name)

##background-color
- bg-{nnn|color} (0<=n<=F, color: any color name)

##text-decoration
- text-decoration-{none|underline|dashed|dotted}

##vertical-align
- vertical-align-{middle|top|bottom}

##display
- display-{inline|block|inline-block|none}

## width, height - maybe later...
- width-{n*20}px (1<=n<=50)
- height-{n*20}px (1<=n<=50)
- min-width-{n*20}px (1<=n<=50)
- min-height-{n*20}px (1<=n<=50)