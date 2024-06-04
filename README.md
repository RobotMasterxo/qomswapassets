LP tokens must be burned or locked.



Adding Your Token to QOMSWAP

To have your token listed on QOMSWAP, please follow these guidelines:
Folder Structure

    Fork the Repository: Start by forking the QOMSWAP repository.

    Create a Folder: Create a folder named with the address of your token contract. This folder will contain the required files for listing your token. Ensure the folder is structured as follows:


0xYourTokenAddress/
    logo.png
    telegram.txt

Requirements for Each File
logo.png

    The logo of your token.
    Size: Ensure the logo is the same size as the example provided in the repository (256x256 pixels).
    Format: The logo must be in PNG format.

telegram.txt

    Content: The content should include the NAME, SYMBOL, and TELEGRAM URL, with no additional text or formatting. It should look like this:


    NAME: Name 
    SYMBOL: Symbol 
    DECIMALS: (if different than 18)
    TELEGRAM: (your telegram link)
    LP BURNED/LOCKED: Qomscan tx where you locked or burned your LP 




