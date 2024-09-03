# cryptogemsERC20code
ERC20 smart contract code

STEPS

Step 1: Copy this code. Go back to the smart-contract file, and copy all the code. If you don't know how to get there, open up a new tab on your browser, and paste in the direct link to the smart contract in my Github repo: https://github.com/cryptokingpin76/cryptogemsERC20code/blob/main/smart-contract

Step 2: Go to https://www.remix.ethereum.org

Step 3: Below FILE EXPLORER, WORKSPACES, and the workspace dropdown box, click on the piece of paper to create a new file. name it whatever you want your token to be called with no spaces in between any words. If you want it to be calle Cute Kitty City, then name the file: CuteKittyCity.sol and hit enter. You HAVE to end the file name with .sol

Step 4: Paste in the code you copied from step 1.

Step 5: Read the instructions I wrote in the code on lines 15-19 and change the details to your token info as you want.

Step 6: Open your Metamask wallet. Once opened, make sure you are on the correct network you want to deploy on(Ethereum, Avalanche, BSC, Polygon, Fantom, etc.)
Make sure you also have the correct wallet open, and make sure you have enough gas to be able to properly deploy your smart contract.
Ethereum can get pricey, maybe up to $30. Any changes would be an additional gas charge like minting, or burning, etc. All the other chains, gas isvery cheap.

Step 7: In Metamaks, click on the 3 dots in the top right. Click on connected sites. If you're not connected already to Remix, click manually connect.

Step 8: On Remix, click on the Solidity Compiler icon(right above the Ethereum looking icon on the left side of the screen).

Step 9: Make sure your compiler version selected is 0.8.26. Click on the arrow to the right of Advanced Configurations. For EVM Version, choose London. Now click the big blue Compile button below.

Step 10: Once you see a green check mark on the right on the Compiler icon, click the icon below it that looks like the Ethereum icon.

Step 11: Under Environment, choose Injected Provider - MetaMask

Step 12: Under Contract, make sure it says Custom Token...... Now click on the orange Deploy button below that.

Step 13: When Meta Mask pops up, confirm the transaction. You should get a green checkmark towards the bottom of the screen on Remix if it was successfully deployed.

Step 14: Whichever blockchain you deployed it to, go to that chain's block explorer. If you don't know what explorer the chain uses, just google the chain you deployed on and explorer.
For example, I deployed this on Fantom. So just Google Fantom Block Explorer. If you are suing a different chain, just change Fantom to whatever chain you're using.
From the Google results, choose the block explorer for your chain. 

Step 15: Go back to Remix. On the left side of the screen below the orange deploy button if you scroll down, you should seeDeployed/Unpinned Contracts. Your should say CUSTOMTOKEN AT .....
Click on the 2 piecs of paper on top of each other icon next to that.

Step 16: Go back to your block explorer. In the search bar there, paste in the contract address you just copied from Remix and then hit enter.

Step 17: You should see several tabs in the middle of the page: transaction, internal transaction, etc. Click on the Contract tab. Now click on Verify and Publish.

Step 18: Go back to Remix and on the left side towards the bottom click on the plug icon. When it opens, in the search bar type flattener. When it pulls it up, click on activate.
Now click on the 2 pieces of paper above the magifying glass on the left side of your screen. Right click on your contract ending with .sol
Click on flatten. now you will have a regular version of your contract, and a flattened version. Open the flattened version by clicking on it. 
Go to line 1 of the code and type this in exactly: // SPDX-License-Identifier: MIT
Now select ALL the code in that flattened contract.

Step 19: Go back to your block explorer where you should still be on the verify and publish screen. Select Solidity single file from the 1st dropdown. Select compiler version v0.8.26+ from the second dropdown. Select MIT License from the 3rd dropdown. Check the terms and service box if it isn't checked already and click on Continue.

Step 20: Click inside the Enter the Solidity Contract Code Below box. Now paste in the flattened contract code you copied from the Remix flattened version of you contract. In the EVM dropdown, choose london. Scroll down and click on verify and publish button.



