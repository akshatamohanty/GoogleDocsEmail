## About

Google Spreadsheet plug-in to batch email, using Google Docs templates. You can easily design your template using a Google Doc and use it to send batch emails

![final_email](./assets/workflow.gif)


## How to install?

- In your spreadsheet, from the `Tools` menu, navigate to the `Script Editor`
- Name the project, add the 4 source files provided here
- Navigate back to your spreadsheet: you'll see a new option `automated-mailing` under the `Add-ons` menu

## How to use?

- Pick a template file from the dropdown; Template files are Google Docs in the same folder, with the delimited variable values
- Make a selection from the spreadsheet, selecting the values you want to populate
- Make sure: 
   - A column with `Email` header exists
   - Headers are provided and correspond to the variables in your template docs
   - Your selected range doesn't include the headers
- Click on `Get Content`
- Click `Next` after verifying the information is correct
- Add email details and click `Email Preview` to see a sample mail
- Click `Batch Email` to send all emails! 

### Is this useful?

<a href="https://www.buymeacoffee.com/iamaatoh" target="_blank"><img height="45px" src="https://cdn.buymeacoffee.com/buttons/v2/default-blue.png" alt="Buy Me A Coffee"></a>
