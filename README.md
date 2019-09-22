# GAS
Shared Google Apps Scripts, you need a google account to access them.  

### [DriveSauceNAO](https://script.google.com/d/1esBRcVLWkp_Xfnx08kWGDy2ka8l-EmrYUX6q640WFa3HtKXHaBsExUYq/edit?usp=sharing)

Uses SauceNAO to automatically sort images from one folder into subfolders, also overwrites the google drive description with the fetched information.

The good thing is that this works completely on google servers, although google changes the IP for the request on set intervals, it is possible that all free searches are already taken so it is advised to use this with an API key.

This still needs works but it does it job for me, so you can take it was template if you want.

### [triggerMe](https://script.google.com/d/1ifx0NzjdasBKSlwUoTG-1JbSg3w83nwqbbREg_kPT_p9mh2kJ2ePukWT/edit?usp=sharing)

Small script to create at and after trigger with parameters.

### [async](https://script.google.com/d/1oYg_C9uCUAnAzePKXX9SxL8b5x-mVnnGWIH-LC-PzzPzhFRqfwrC3ae0/edit?usp=sharing)

The purpose was to start multiple script at once without client intervention, also on googles servers only. Every other solution I found had a client frontend more or less and couldn't be used. So sadly the only way I found was with a blocking post request, it still does work but it hangs the caller script and is limited to 30 seconds before google timeouts the request.

### [sharedFiles](https://script.google.com/d/MVTJyqxeGV5SXEmkYBQm0BXJw_UllaxJx/edit)

Spreadsheet add-on to display all shared files of the user.
