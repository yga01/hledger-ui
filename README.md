This is a single file HTML file that provides a web interface for hledger. Load the file in your browser, throw in your ledger data file and you get three tabs:
- one tab for the transactions. You can edit and append transactions
- one tab for the blaance sheet
- one tab for the P&L.

That's it. Super simple, should be self-explanatory.

Please note:
- I am in Europe and my ledger data files use 'EUR' as the currency symbol
- I have not implemented multi-currency, it is just EUR
- my accounts start with ass: lia: inc: exp. I am not sure of that is standard hledger lino but it is what I use at the moment. I may need to change that for others to use this web-interface, not sure.
- my dates are in 2026/01/31 format. I don't think my regexp parses other formats.

So more qork may be required to make this a usefull tool for other people. For now you're free to try and leave comments.

Final note: No I am NOT a programmer. I have some basci knowledge of Javascript and Python and Pascal and stuff like that, but I am not a programmer. This web interface I built just by talking to Claude at claude.io. Amazing tool!

