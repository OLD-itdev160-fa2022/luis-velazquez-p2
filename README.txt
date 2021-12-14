//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

▒█▀▀▀█ ▀█▀ ▒█▀▄▀█ ▒█▀▀█ ▒█░░░ ▒█▀▀▀ 　 ▒█▀▀█ ▒█░▒█ ▒█▀▀▄ ▒█▀▀█ ▒█▀▀▀ ▀▀█▀▀ 　 ▀▀█▀▀ ▒█▀▀▀█ ▒█▀▀▀█ ▒█░░░ 
░▀▀▀▄▄ ▒█░ ▒█▒█▒█ ▒█▄▄█ ▒█░░░ ▒█▀▀▀ 　 ▒█▀▀▄ ▒█░▒█ ▒█░▒█ ▒█░▄▄ ▒█▀▀▀ ░▒█░░ 　 ░▒█░░ ▒█░░▒█ ▒█░░▒█ ▒█░░░ 
▒█▄▄▄█ ▄█▄ ▒█░░▒█ ▒█░░░ ▒█▄▄█ ▒█▄▄▄ 　 ▒█▄▄█ ░▀▄▄▀ ▒█▄▄▀ ▒█▄▄█ ▒█▄▄▄ ░▒█░░ 　 ░▒█░░ ▒█▄▄▄█ ▒█▄▄▄█ ▒█▄▄█

-------------PROJECT DESCRIPTION:--------------------------------------------------------------------------------------------------------------

Hello, thank you for checking out my "Simple Budget Tool". With this tool, you can provide an item's name, price, and quantity, 
and it will sum up and provide a total. It is helpful for keeping track of large item lists and returning an accurate figure in a short amount of 
time.
Did you make a mistake while inputting data? No worries, you can easily adjust the item quantity and the total figure will be adjusted immediately.

Thanks,
Luis Velazquez
ITDEV 160

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

-------------USER REQUIREMENTS:--------------------------------------------------------------------------------------------------------------

1. All input must be made in plaintext.  

2. "Item Name" can be any UTF-8 character. 

3. "Price per Unit" must be any UTF-8 number character. Negative numbers will be treated as positive. 

4. Click the "add item" button once you have finished adding information for a single product. The form will clear all data and your previously entered item will appear in
   the current cumulative list. 

5. The cumulative total will be displayed every time you hit the "Add Item" button. 

6. If you notice an error in your data you can either adjust the item quantity by clicking the "+" or "-" buttons, or remove the entire entry by clicking the "Remove" button. 

7. There are no limits to how many entries you can make. 

8. Clicking the refresh button will clear all forms and all data. You will not be given a warning, and you may lose work. 
   You must record your data somewhere else if you wish to keep it.



-------------SOFTWARE REQUIREMENTS:--------------------------------------------------------------------------------------------------------------

1. A modern web-based browser is required to use this tool. It must allow javascript code to be executed. 

2. Form data must be entered manually via a keyboard (or touch input via mobile device). Only individual data points can be copied and pasted. 
   The budget tool does not currently allow the input of large data sets (such as excel spreadsheets)
   
3. All figures are shown with 2 decimal places (corresponding to cents). The exception are quantity figures are shown as whole numbers. 

4. Source code can be found here: https://github.com/itdev160-fa2022/luis-velazquez-p2.git


//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////