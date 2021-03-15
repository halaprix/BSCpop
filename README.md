# BSCpop

BSCpop is a randomly genrated NFT token available on BSC (it not related to Binance in any way, the Binance logo is used as canvas for pseudo artsy - psudo randomly generated art)

The price curve is linear, starting at 0.01 BNB for a BSCpop piece. Each new piece increases the price by 0.01 BNB. - 95% of the price is kept in the bonding curve reserve. 5% goes to the creator.
There exists 6 colours, with #F3BA2F, #FE0879, #FF82E2, #70BAFF and #0037B3 being equally likely (~20%). - #EDFFB1 is rare (~1/256). - The colours are chosen from the first 9 bytes of a psuedo-randomly generated 32 byte hash.
A maximum of 46656 (6^6) potential combinations can thus exist.
Duplicates are possible with different hashes.
Every BSCpop is stored as its hash on BSC and can be auto-generated directly from the smart contract into an SVG blob. Thus, if this website goes away, you would always be able to own and view your BSCpop.
It uses the ERC721 NFT standard, and uses the 'image_data' field from OpenSea to enable the metadata to be more readily viewed by others (vs directly pulling it from BSC).
It also uses the default "image" metadata allowing support for mutiple wllatets to display the tokens.
NOTE: This code is *unaudited*. Caution is advised unless you want to take the risk.
credits to https://neolastics.com/
