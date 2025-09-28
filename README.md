# EVS Generator

## Overview
EVS Generator is an automated tool designed for generating Discord accounts with email verification. This tool streamlines the account creation process by handling email verification, form filling, and captcha solving.

## Setup Instructions

1. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Run the application:
   ```
   python main.py
   ```

## Output Files

All generated data is saved in the `output` directory:

- `output/accounts.txt` - Contains email:password:token combinations
- `output/itok.txt` - Stores inbox tokens for email verification
- `output/tokens.txt` - Stores generated EVS tokens

## Branding
Developed by HUSTLE HQ | [discord.gg/hustlehq](https://discord.gg/hustlehq)