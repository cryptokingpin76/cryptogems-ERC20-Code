# cryptogemsERC20code
ERC20 smart contract code

1. To customeize this smart contract, you need to change itmes on lines: 34, 50, 51, 52, and 53.

Line 34: after the word contract, there should be a space and then the name of your token/contract. It needs to be words only and be one string of words, no spaces in between the words.
For example, if you want your token name to be cute kitty city, in line 34 you need to type it out as CuteKittyCity
Line 34 should look like this in this example: contract CuteKittyCity is ERC20Interface, SafeMath {

Line 50: after name = you need to change the name of your token to whatever you want it it to be. It should match your exact contract name as you wrote it from line 34.
Sticking with the CuteKittyCity example, this line should look like this: name = "CuteKittyCity";

Line 51: after symbol = you need to put a token symbol. Similar to a ticker for a stock would have. 
Line 51 should look like this in this example: symbol = "KCC";
Your token symbol should be a shorter version of you token name, and in all capital letters. It can be up to 12 symbols long I believe but the shorter the better as it's easier to remeber.

Line 52: This is where you choose the number of decimals you want. It can be from 1-18 decimals.
Line 52 should look like this if we want to have 10 decimals for example: decimals = 10;
If you want a number other than 10, just replace it with that number. It has to be a whole number between 1-18.

Line 53: This is where you decide on how many tokens you will ever have TOTAL. 
Your supply will be whatever amount you decide to create when you deploy your smart contract. With this code, there is no mint function so when you deploy your contract, you can never create any more of your token.
The total supply here will be for example 1 million tokens. Normally that would be typed as: 1000000000
Instead, what you would need to do here, is have the total supply you want to create, followed by 18 zeros so it displays correctly.
Let's say we want to create 77 billion tokens, line 53 should look like this: _totalSupply = 77000000000000000000000000000000;

