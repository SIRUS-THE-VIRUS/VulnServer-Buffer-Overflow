# VulnServer-Buffer-Overflow

Download VulnServer https://github.com/stephenbradshaw/vulnserver  

Download a debugger like Immunity https://www.immunityinc.com/products/debugger/    

Step 1: FUZZ until the program crashes  
Step 2: Find the Offset  
Step 3: Find a JMP ESP   
Step 4: Overwrite the EIP with the JMP ESP  
Step 5: add some NOOP then drop the shellcode  
