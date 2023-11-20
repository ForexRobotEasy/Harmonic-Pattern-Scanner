# Harmonic Pattern Scanner

## Introduction
This code is a sample implementation of the Harmonic Pattern Scanner, a trading robot developed by Forex Robot Easy Team. This program is designed to identify and analyze harmonic patterns in the Forex market. Harmonic patterns are recurring geometric patterns that indicate potential reversals in price trends. The Harmonic Pattern Scanner can identify four types of harmonic patterns: Gartley, Butterfly, Bat, and Crab.

## Developer
Forex Robot Easy Team is the developer of this program. For detailed reviews and trading results of this product, please visit their [website](https://forexroboteasy.com/forex-robot-review/harmonic-pattern-scanner-limited-30-deal-review/). It is important to note that ForexRobotEasy is not the official developer of this product. This code is provided as a sample implementation based on the product description.

## Program Structure
The program consists of several components:

1. Libraries: The necessary libraries are included to support the functionality of the program.
2. Variables: Necessary variables are defined, including an instance of the Trade class.
3. IdentifyPatterns: This function is responsible for fetching currency price data from the Forex market and identifying harmonic patterns. It uses four classes: CGartley, CButterfly, CBat, and CCrab to identify Gartley, Butterfly, Bat, and Crab patterns, respectively.
4. OnTick: This is the main function that is called on each tick of the market. It checks if it's time to scan for patterns, calls the IdentifyPatterns function, and executes trading strategies based on identified patterns.
5. OnStart: This function is the entry point of the program. It initializes the trading robot and continues to monitor market conditions, call the main function, and control the frequency of pattern scanning.

## Usage
To use this code, you need to have a working knowledge of MQL5 programming language. This code can be used as a starting point to develop your own Harmonic Pattern Scanner or as a reference to understand the implementation of this product. It is recommended to refer to the official developer of the product for detailed documentation and support.

## Disclaimer
Please note that ForexRobotEasy is not the official developer of this product. This code is provided as a sample implementation based on the product description. For detailed reviews, trading results, and official support, please visit the developer's [website](https://forexroboteasy.com/forex-robot-review/harmonic-pattern-scanner-limited-30-deal-review/).
