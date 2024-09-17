Since the ori package is probably not maintained anymore (last update 2 years ago), so a quick and dirty solution is implemented by modifying the compiled code.

This version is specifically targeted at barChart element to fix label length too long and cutted off. 

A props called labelHeight is included to adjust the height of the vertical label container. To ensure the entire label is displayed, calculate the maximum length of the label and dynamically adjust the labelHeight prop.