# ROM DUMP REPO FOR DLS
Please Add the ROM names to your project description.json file in this fashion
<br/>
 ```"AllCustomChipNames":["CHIPNAME","SECOND CHIPNAME IF THERE IS MORE THAN ONE"],```
<br/>
replace 'CHIPNAME' with the chip you put in and add a ',' if you added it in the middle of your list
Then make a bit at the bottom of the file before the closing brackets
<br/>
      ```"Chips":["CHIPNAME","SECOND CHIPNAME IF THERE IS MORE THAN ONE"],
      "IsToggledOpen":true,
      "Name":"ROMS" ```
