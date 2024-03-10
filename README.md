# mfr-steamlit-plus-bedrock

First and foremost almost all of the credit for this lab goes to the venerable Tim Long @ Snowflake. Thanks Tim!

## Pre-requisites: 
- Snowflake account with Streamlit
- AWS account with access to Bedrock models

## Instructions

1. Download the Otto PDF files and upload them to an internal stage named "repair_manuals".
2. Follow the code in scripts 1-4 to create a secure connection to AWS Bedrock and a function around along with the functions to process the files.
3. Copy and past the code in the 5th script to create a Streamlit app in Snowflake.
4. Have fun with your Manufacturing app!

## Things to look out for
1. Make sure to create a separte database in Snwoflake to house the internal stage, the streamlit app and all of the the other Snowflake objects with this lab.
2. A small or xsmall warehouse should suffice for this demo.
3. This demo utilizes AWS temporary tokens so be aware the calls to Bedrock will fail once those keys and tokens expire.
