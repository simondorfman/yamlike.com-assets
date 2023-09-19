# yamlike.com-assets

This repository contains assets used in articles on [www.YamLike.com](https://www.yamlike.com). YamLike is a newsletter about blockchain, crypto, web3, data & software development; written by Simon Dorfman.

## License

Works in this repository are © Simon Dorfman and licensed under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/). (See LICENSE.md in this same directory.)

Here's an example of how you can share attribution for an image from this repository:

> [Fund Solo Ethereum Validator Node with IRA – Sequence Flow of $USD to ETH & back to $USD](https://www.yamlike.com/archive/fund-solo-ethereum-validator-node-with-ira) by [Simon Dorfman](https://www.yamlike.com/) is licensed under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

Here's that same example attribution in html:

```
<a href="https://www.yamlike.com/archive/fund-solo-ethereum-validator-node-with-ira">Fund Solo Ethereum Validator Node with IRA – Sequence Flow of $USD to ETH &amp; back to $USD</a> by <a href="https://www.yamlike.com/">Simon Dorfman</a> is licensed under <a href="http://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a>
```

Here's that same example attribution in markdown:

```
[Fund Solo Ethereum Validator Node with IRA – Sequence Flow of $USD to ETH & back to $USD](https://www.yamlike.com/archive/fund-solo-ethereum-validator-node-with-ira) by [Simon Dorfman](https://www.yamlike.com/) is licensed under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)
```

## What to do with Mermaid.js files (files ending with ".mmd")

1. Install this tool: https://github.com/mermaid-js/mermaid-cli
2. Run this command to convert a mermaid.js file to a PDF:  
`mmdc -f -i 0_sequence_flow_of_usd_to_eth_and_back_to_usd.mmd -o 0_sequence_flow_of_usd_to_eth_and_back_to_usd.pdf`
    * The `-f` makes the PDF render as one big page (instead of trying to paginate it).
3. Open the PDF in a vector tool like Affinity Designer, Inkscape, or Adobe Illustrator; do any final touch-up; export to PNG or SVG. (For PNGs, I usually export at 1800 pixel width.)
4. Or, if no touch-up needed, skip 2 & 3, and export directly to PNG:  
`mmdc -f -i 0_sequence_flow_of_usd_to_eth_and_back_to_usd.mmd -o 0_sequence_flow_of_usd_to_eth_and_back_to_usd.png`  
...and/or SVG:  
`mmdc -f -i 0_sequence_flow_of_usd_to_eth_and_back_to_usd.mmd -o 0_sequence_flow_of_usd_to_eth_and_back_to_usd.svg`
5. For PNGs, I like to reduce file size by using [optipng](https://optipng.sourceforge.net); like this:  
`optipng 3_sequence_flow_of_usd_to_eth_and_back_to_usd.png -o 2 -strip all`

## What to do with Affinity Designer files (.afdesign)

Whenever I share an .afdesign file, I also try to export a .pdf file of the same name. That way, if you don't use Affinity Designer, hopefully you can open the .pdf in your vector editor of choice (e.g. Inkscape, Adobe Illustrator).