# BBB-PoE

PoE Hat for BeagleBone Black

This hat adds Power over Ethernet to the BeagleBone Black by passing the ehternet traffic through this board into the ethernet jack on BBB board. It does not include another ethernet PHY. The PoE circuits provide 12V out which is regulated to 5V for the BBB. The BBB regulates further to 3.3V. In this case my desired application needed 12V and 5V sources.

The schematic and floorplanning are complete, but I didn't finish layout since the project changed focus. If anybody wants to extend or complete this project I would consider pull requests.
