# Cookie Clicker Automation

A Python script that automates playing the [Cookie Clicker](http://orteil.dashnet.org/experiments/cookie/) game using Selenium WebDriver.

## Features

- Automatically clicks the cookie
- Purchases upgrades every 5 seconds based on available money
- Buys the most expensive affordable upgrade
- Runs for 5 minutes and displays cookies per second at the end

## Requirements

- Python 3.11
- Selenium WebDriver

## How It Works

The script:
1. Opens the Cookie Clicker game in Chrome
2. Continuously clicks the cookie
3. Every 5 seconds, checks available upgrades and purchases the most expensive one possible
4. After 5 minutes, displays the final cookies per second rate and exits

Note: Make sure you have Selenium and Chrome WebDriver installed before running the script.
