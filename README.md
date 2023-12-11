# README for Simple Bidding Program

## Overview
This Python script is a basic bidding application. It allows multiple users to enter their names and bid amounts, and then determines the highest bidder. This script is particularly useful for conducting simple auctions or bidding games.

## Features
- User-friendly input prompts for entering bidder names and bid amounts.
- Dynamically stores all bids in a dictionary for easy access and manipulation.
- A function to find and display the highest bidder and the winning bid amount.
- Continues to accept bids until the user indicates that bidding is finished.

## Requirements
To run this script, you will need:
- Python 3.x installed on your machine.
- The `art.py` module, which includes the `logo` variable used in the script.

## How to Use
1. **Starting the Program:** Run the script in a Python 3.x environment. Upon execution, the program will display an ASCII art logo from `art.py`.

2. **Entering Bids:** 
   - When prompted, each bidder should enter their name and bid amount.
   - The bid amount should be entered as a whole number (without any currency symbols).

3. **Continuing or Ending the Bidding Process:**
   - After each bid, the program asks if there are more bidders.
   - To enter more bids, type 'yes'. To end the bidding, type 'no'.

4. **Determining the Winner:**
   - Once 'no' is entered, the program stops accepting bids and calculates the highest bidder.
   - The winner's name and their bid amount are displayed.

5. **Ending the Program:** The program automatically exits after displaying the highest bidder.

## `art.py` Module
Your `art.py` should contain:
```python
logo = '''
                         ___________
                         \         /
                          )_______(
                          |"""""""|_.-._,.---------.,_.-._
                          |       | | |               | | ''-.
                          |       |_| |_             _| |_..-'
                          |_______| '-' `'---------'` '-'
                          )"""""""(
                         /_________\\
                       .-------------.
                      /_______________\\
'''
```
This ASCII art is displayed at the start of the program.

## Note
- The program does not handle invalid input (like non-integer bid values) or offer robust error handling.
- The script is intended for educational or entertainment purposes and is not suitable for real auctions.

Feel free to modify and improve the script according to your needs!